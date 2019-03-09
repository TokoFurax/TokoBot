const Discord = require('discord.js');

var myBot = new Discord.Client();
var prefix = "T/"

/* Aides */

myBot.on("ready", () => {
    myBot.user.setPresence({ game : { name : 'http://generalcraft.cf', type: 0} });
    console.log("Bot sur une plage paumée");
})

myBot.on('message', data => {
if (data.content === prefix + 'rpg maker xp'){
    data.channel.send('http://www.final-rpg.com/rpg_maker_xp-telecharger-installation.html ,clic sur la deuxième image et installe le ,puis installer http://www.mediafire.com/file/fzl5rz6asgj1ppk/rpg_maker_xp.rar');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'unity'){
        data.channel.send('https://store.unity.com/download?ref=personal');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'python'){
        data.channel.send('https://www.python.org/downloads/');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'visual studio'){
        data.channel.send('https://code.visualstudio.com/');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'mc'){
        data.channel.send('http://generalcraft.cf');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'MC'){
        data.channel.send('http://generalcraft.cf');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'aide'){
        data.channel.send('les commandes possibles sont: T/rpg maker xp, T/unity, T/python et T/visual studio, T/bot pc, T/bot android, photoshop crack');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'bot pc'){
        data.channel.send('https://www.youtube.com/watch?v=FMijzVzh4MQ&t=1s');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'bot android'){
        data.channel.send('https://www.youtube.com/watch?v=XkIBT1ONfOc&index=2&t=0s&list=WL');
}
})
myBot.on('message', data => {
    if (data.content === prefix + 'photoshop crack'){
        data.channel.send('https://www.youtube.com/watch?v=CI5zI-1XjYM');
}
})
myBot.on('message', message => {
    if(message.content.startsWith( prefix + "clear")) {
        if(!message.guild.member(message.author).hasPermission("MUTE_MEMBERS")) return message.channel.send("Vous n'avez pas la permission !");

        let args = message.content.split(" ").slice(1);

        if(!args[0]) return message.channel.send("Tu dois préciser un nombre de messages à supprimer !")
        message.channel.bulkDelete(args[0]).then(() => {
            message.channel.send(`${args[0]} messages ont été supprimés !`);
            console.log("clear")
    });
}
})

myBot.login("NTUwMzI3ODQ1NTg3Nzc5NjA0.D1hOBw.8tvz6YCatzzLuGemE6rx0eBcVVY");
