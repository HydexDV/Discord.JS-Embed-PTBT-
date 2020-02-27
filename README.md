
## Como criar uma embed? 

é necessario definir a embed! usando oque esta abaixo, pode definir com qualquer tipo de nome eu gosto dar o nome de acordo com oque irei fazer EX: vou fazer uma carteira logo defino a embed como wallet/carteira.
```js
       if(cmd === '!embed'){
      let coisa = new Discord.RichEmbed()
     
    }
``` 
logo iremos fazer ele enviar a embed no canal.
```js
      if(cmd === '!embed'){
      let coisa = new Discord.RichEmbed()


      message.channel.send(coisa);
    }

``` 
Entre os 2 devemos colocar as definições de como você vai querer sua embed 
**AVISO! Não coloque mais nada alem das definiçoes da embed entre eles!**

## Definições da embed

Agora você ira aprender a "Customizar" sua embed para deixa-la ao seu gosto.

#### • setAuthor("texto","imagem (OPCIONAL)") 
```js
    if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setAuthor("Oi eu sou o Author","https://cdn0.iconfinder.com/data/icons/free-social-media-set/24/discord-512.png")
      message.channel.send(coisa);
    }
  
});
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682576291240738870/unknown.png "Title")

#### • .setDescription("texto") 
```js
       if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setDescription("Oi eu sou uma description [e eu sou um link clicavel](https://www.youtube.com/channel/UCTbR2nrS_LR5jR6BpBjjG_A)")
      message.channel.send(coisa);
    }
  
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682577482649436311/unknown.png "Title")

#### • .setTitle("texto") 
Nesse caso utilizei o ".setDescription" junto para demonstrar como ele pode ser usado!
```js
        if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setTitle("Oi eu sou um title")
      .setDescription("eu sou a descrição de um title")
      message.channel.send(coisa);
    }
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682578857819504651/unknown.png "Title")

#### • .setFooter("texto","Icone ou imagem") 
```js
if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setTitle("Oi eu sou um title")
      .setDescription("eu sou a descrição de um title")
      .setFooter("Oi eu sou um footer","https://cdn0.iconfinder.com/data/icons/free-social-media-set/24/discord-512.png")
      message.channel.send(coisa);
    }
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682579682008498186/unknown.png "Title")

#### • .setImage("imagem") 
```js
  if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setTitle("Oi eu sou um title")
      .setDescription("eu sou a descrição de um title")
     .setImage("https://cdn0.iconfinder.com/data/icons/free-social-media-set/24/discord-512.png")
      message.channel.send(coisa);
    }
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682580281722667019/unknown.png "Title")
#### • .setThumbnail("imagem") 
```js
       if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setTitle("Oi eu sou um title")
      .setDescription("eu sou a descrição de um title")
      .setThumbnail("https://cdn0.iconfinder.com/data/icons/free-social-media-set/24/discord-512.png")
      message.channel.send(coisa);
    }
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682580624694968351/unknown.png "Title")
#### • .setColor("hex,rgb") 
```js
  if(cmd === '!teste'){
      let coisa = new Discord.RichEmbed()
      .setTitle("Oi eu sou um title")
      .setDescription("eu sou a descrição de um title")
     .setColor("#ff0000")
      message.channel.send(coisa);
    }     
```
![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682581345452687389/unknown.png "Title")
