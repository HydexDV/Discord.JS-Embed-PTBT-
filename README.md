
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

#### - setAuthor("TEXTO","IMAGEM (OPCIONAL)") 

![Alt text](https://cdn.discordapp.com/attachments/682575921727012902/682576291240738870/unknown.png "Title")
