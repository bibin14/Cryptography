# Cryptography
Encryption &amp; Decryption Algorithm
<div class=WordSection1>

<p class=MsoListParagraph style='text-indent:-.25in'><span style='font-family:
Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><b><u>Hash</u></b></p>

<p class=MsoNormal style='margin-left:.5in'>Hash functions are fundamental to
modern cryptography. These functions map binary strings of an arbitrary length
to small binary strings of a fixed length, known as hash values. A
cryptographic hash function has the property that it is computationally
infeasible to find two distinct inputs that hash to the same value. Hash
functions are commonly used with digital signatures and for data integrity.</p>

<p class=MsoListParagraph style='text-indent:-.25in'><span style='font-family:
Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><b><u>Symmetric</u></b></p>

<p class=MsoNormal style='margin-left:.5in'>Symmetric encryption uses a single
key to encrypt and decrypt. Both parties (encryptor and decryptor) must share
the same secret key.</p>

<p class=MsoListParagraph style='text-indent:-.25in'><span style='font-family:
Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><b><u>Asymmetric </u></b></p>

<p class=MsoNormal style='margin-left:.5in'>Asymmetric encryption uses a pair
of keys to encrypt and decrypt. There is a &quot;public&quot; key which is used
to encrypt. Decrypting, on the other hand, requires both the &quot;public&quot;
key and an additional &quot;private&quot; key. The advantage is that people can
send you encrypted messages without being able to decrypt them.</p>

<p class=MsoNormal style='margin-left:.5in'><b><i><u>Note:</u></i></b> The only
provider supported is the &quot;<a
href="https://msdn.microsoft.com/en-us/library/system.security.cryptography.rsacryptoserviceprovider(v=vs.110).aspx">RSACryptoServiceProvider</a>&quot;</p>

<p class=MsoListParagraph style='text-indent:-.25in'><span style='font-family:
Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><b><u>Data</u></b></p>

<p class=MsoNormal style='margin-left:.5in'>Data represents Hex, Byte, Base64,
or String data to encrypt/decrypt;</p>

<p class=MsoListParagraphCxSpFirst style='margin-left:1.0in;text-indent:-.25in'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>Use
the .Text property to set/get a string representation </p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:1.0in;text-indent:-.25in'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>Use
the .Hex property to set/get a string-based Hexadecimal representation </p>

<p class=MsoListParagraphCxSpLast style='margin-left:1.0in;text-indent:-.25in'>3.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>Use
the .Base64 to set/get a string-based Base64 representation</p>

</div>
