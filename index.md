## Welcome to Project Black-Hole
### Developer: Exspiravit.sh (https://github.com/exspiravit-sh)

#### The BlackHole Project is based on and influenced by the TOR and I2P Networks, in the sense that TOR is no longer as bulletproof as we once thought, even though is still a great program, it's outdated.

#### Where BlackHole is different, basically it's a similar idea, only instead of having layers of encryption, the hash and keys are sent seperately. You send a request to the server, your data is encrypted using a random method, and your keys to the hash are also encrypted, not sent with the encryption though, they're sent by another computer in the network. 

#### This continues for the other computers in the network, the keys being seperate from the hashes at all times. As it gets to the server, everything is still encrypted, possibly multiple types, and the server decrypts the keys, which are then used to decrypt the hashes that are sent, it sends back what you requested and the same happens again, you recieve your data and your computer decrypts the keys, decrypting the data and giving you what you requested.

#### Where it's more secure is how everything is encrypted and sent. The speed comes from the cpu encrypting the data and keys, both encrypted in different methods, the keys being somewhat hardcoded, meaning it'll be hard to guess, very hard. Even if you get the right method, you'd need the right keys, which are with another computer with a different encryption method, and their hash is also different, making it even harder since you'd need to find the right keys, and decrypt the keys to even begin decrypting the hash you sent. Meaning, a MITM attack is almost impossible.

#### It's also going to be more secure since I'm designing it's own seperate network protocol for it, which will give me more control over the encryption and the traffic, meaning if I wanted to, I could make sure the ISP (Internet Supplier) Never sees anything coming or going, but knowing that the program is being used, or hopefully if I'm able to design this properly, it will be transparrent.

#### I should also add, since the encryption is random and is being done by the cpu, not only will it be fast, but it also means It'll be harder for people to even see what's going to and from the server, even if they had the keys,you wouldn't know where it's going, and the data the server recieves will also be encrypted in a way, meaning the server understands it, but anyone reading it wouldn't understand a word.

### Legal disclaimer - Usage of Black-Hole for malicious intent without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.
