fix a lot of bugs in https://github.com/FlorianREGAZ/Python-Tls-Client

the orginal FlorianREGAZ can not handle the headers of two sequence requests. The second one will use the first one's headers.

the orginal FlorianREGAZ can not handle bineary return, it return wrong answers if the respone is video or image.

the orginal FlorianREGAZ can not post multipart, this fix the problem using files=.

the library is used to customize the fingerprint of ssl handshake.
