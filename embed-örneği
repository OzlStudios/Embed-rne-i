const Discord = require('discord.js')
exports.run = (client, message, args) => {

  message.channel.send(
    new Discord.RichEmbed()
      .setColor('#000000')
      .setTitle("🔷 Embed Örneği") //🔷 Embed Örneği Yazan Yere İstediğiniz Komut Başlığınızı Girin
      .addField('Buraya Bir Başlık Yazın','Buraya Bir İstediğiniz Bir Yazı Yazabilirsiniz')//"Buraya Bir İstediğiniz Bir Yazı Yazabilirsiniz" Bu Kısma İstediğiniz Bir Yazı Girebilirsiniz
        .addField('Buraya İstediğiniz Başlığı Girin.', 'Açıklama', true)//Başlık VE Açıklmaları İstediğiniz Gibi Yazabilirsiniz
        .addField('Buraya İstediğiniz Başlığı Girin', 'Açıklama', true)//Başlık VE Açıklmaları İstediğiniz Gibi Yazabilirsiniz
        .addField("Bunu Editleyerek İstediğinizi Yapabilirsiniz", "CSD's CODE SERVER")
        .setTimestamp()
        .setFooter("Bot İsmi Veya Başka Birşey Yazabilirsiniz")
  )
}

exports.conf = {
  enabled: true,
  guildOnly: true,
  aliases: [],
  permLevel: 0
}

exports.help = {
  name: 'embed-örneği',
  description: 'Embed Örneği',// Komut Açıklamsı Yazın
  usage: 'embed-örneği'
}
   
