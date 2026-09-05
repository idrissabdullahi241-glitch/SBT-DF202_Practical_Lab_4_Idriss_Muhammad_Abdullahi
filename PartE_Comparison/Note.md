Comparison of Original and Stego Images

The original carrier image and the stego image were examined and compared using file size analysis, SHA-256 hash calculations, hexadecimal
inspection with xxd, and string analysis. Although both images appeared visually identical when opened, their hash values were different
because the stego image contained concealed information. This demonstrates how steganography can modify digital data without producing
noticeable visual changes. The comparison successfully showed the difference between visual appearance and underlying binary content.

The original and stego images appear visually identical because steganography modifies only small portions of image data. The Least
Significant Bit (LSB) technique changes bits that do not noticeably affect image appearance. Although the images look the same to the human
eye, their digital contents differ, resulting in different hash values.
