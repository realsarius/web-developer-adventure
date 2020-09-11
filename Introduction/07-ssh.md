# Secure Shell (SSH)

The SSH protocol (also referred to as Secure Shell) is a method for secure remote login from one computer to another. It provides several alternative options for strong authentication, and it protects the communications security and integrity with strong encryption. It is a secure alternative to the non-protected login protocols (such as telnet, rlogin) and insecure file transfer methods (such as FTP).

SSH protokolü (Secure Shell olarak da adlandırılır), bir bilgisayardan diğerine uzaktan güvenli oturum açma yöntemidir. Güçlü kimlik doğrulama için birkaç alternatif seçenek sunar ve güçlü şifreleme ile iletişim güvenliğini ve bütünlüğünü korur. Korumasız oturum açma protokollerine (telnet, rlogin gibi) ve güvenli olmayan dosya aktarım yöntemlerine (FTP gibi) göre güvenli bir alternatiftir.

# SSH provides strong encryption and integrity protection

Once a connection has been established between the SSH client and server, the data that is transmitted is encrypted according to the parameters negotiated in the setup.The traffic between the communicating parties is protected with industry standard strong encryption algorithms (such as AES (Advanced Encryption Standard)), and the SSH protocol also includes a mechanism that ensures the integrity of the transmitted data by using standard hash algoritms (such as SHA-2 (Standard Hashing Algorithm)).

SSH istemcisi ile sunucu arasında bir bağlantı kurulduktan sonra, iletilen veriler kurulumda belirli parametrelere göre şifrelenir. İletişim kuran taraflar arasındaki trafik, endüstri standardı güçlü şifreleme algoritmaları (AES (Advanced Encryption Standard) gibi) ile korunur ve SSH protokolü ayrıca, standart karma algoritmalar (SHA gibi) kullanarak iletilen verilerin bütünlüğünü sağlayan bir mekanizma içerir. SHA-2 (Standard Hashing Algorithm)).

# SFTP file transfer protocol

The [SFTP (SSH File Transfer Protocol)](https://www.ssh.com/ssh/sftp/) is probably the most widely used secure file transfer protocol today. It runs over SSH, and is currently documented in [draft-ietf-secsh-filexfer-02](https://assets.ctfassets.net/0lvk5dbamxpi/7tKyATFtzJv1k27E2Ucc2M/24d0c903741607757509f66183afa9fc/draft-ietf-secsh-filexfer-02)

SFTP (SSH Dosya Aktarım Protokolü) muhtemelen günümüzde en yaygın kullanılan güvenli dosya aktarım protokolüdür. SSH üzerinden çalışır ve şu anda draft-ietf-secsh-filexfer-02'de belgelenmiştir.

---

Bir bilgisayardan diğerine uzaktan güvenli oturum açma yöntemi, SFTP(SSH file transfer protocol) ile güvenli bir şekilde dosya alışverişi yapabiliriz. SSH, AES(advanced encrpytion standard) ve SHA-2(Standard hashing algortihm) gibi şifreleme algoritmalarıyla güvenlidir.

---

# Useful Links

[SSH - ssh.com](https://www.ssh.com/ssh/protocol/)
[SSH File Transfer Protocol - Wikipedia](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol)

## Over the Wire: Bandit

`$ find /tmp -name core -type f -print | xargs /bin/rm -f` - Find files named core in or below the directory /tmp and delete them.  Note that this will work incorrectly if there any filenames containing newlines, single or double quotes, or spaces.

`$ cat ./spaces\ in\ this\ filename` - Spaces in filename

`$ ls -a -l` - -a all, -l long listing format

`$ find . -type f -size 1033c \! executable`
