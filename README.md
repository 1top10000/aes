# aes
1번 줄
```js
window.AdvancedEncryptionStandardfips197 = 'Advanced_Encryption_Standard';
```
이거 원하는 이름으로 변경
```js
Advanced_Encryption_Standard.Cipher([ /*크기16입력*/ ], [ /*크기16키*/ ])
Advanced_Encryption_Standard.InvCipher([ /*크기16입력*/ ], [ /*크기16키*/ ])
Advanced_Encryption_Standard.Encryption([ /*크기16입력*/ ], [ /*크기16키*/ ], ( /*Padding(0x00~0xFF)*/ ), [ /*크기16IV*/ ])
Advanced_Encryption_Standard.Decryption([ /*크기16입력*/ ], [ /*크기16키*/ ], ( /*Padding(0x00~0xFF)*/ ), [ /*크기16IV*/ ])
```
