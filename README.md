JuJuCrypt
=========

Currently JuJuCrypt supports generation of SHA 256 hashes from strings for Haxe 3. But support for other hashing methods is planned.

###Install
Just enter the following: ```haxelib git JuJuCrypt https://github.com/jujulian1987/JuJuCrypt.git```
and add ```<haxelib name="JuJuCrypt" />``` to your ".nmml" file and you are ready to go.

###Usage
You need to import ```import juju.crypt.SHA256Hash;```. Then you are able to generate a SHA 256 hash with the following command `SHA256Hash.hash("Haxe 3")`

Which returns a hash as string ```aa4b24174d92fb2b39a14d21025dd2ac0c67c96e53b45bb916d893654bf160fb```

That's it ;)!
