const Discord = require('discord.js');
const client = new Discord.Client();
var prefix = "?"// البرفكس هنا

client.on('ready', () => {
  console.log(`Logged in as ${client.user.tag}!`);
  console.log('')
  console.log('')
  console.log('╔[═════════════════════════════════════════════════════════════════]╗')
  console.log(`[Start] ${new Date()}`);
  console.log('╚[═════════════════════════════════════════════════════════════════]╝')
  console.log('')
  console.log('╔[════════════════════════════════════]╗');
  console.log(`Logged in as * [ " ${client.user.username} " ]`);
  console.log('')
  console.log('Informations :')
  console.log('')
  console.log(`servers! [ " ${client.guilds.size} " ]`);
  console.log(`Users! [ " ${client.users.size} " ]`);
  console.log(`channels! [ " ${client.channels.size} " ]`);
  console.log('╚[════════════════════════════════════]╝')
  console.log('By Diamond Codes')
  console.log('╔[════════════]╗')
  console.log(' Bot Is Online')
  console.log('╚[════════════]╝')
  console.log('')
  console.log('')
});
const Discord = require('discord.js');
const fs = require("fs");
const moment = require("moment");
const client = new Discord.Client();
var prefix = "="

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

client.on('ready', () => {

    console.log('By X_KillerYT')
    console.log('DiamonCodes')
    console.log('@!                     X_KillerYT#0661')
    console.log('DiamondCodes')

  });
  

client.on('message', async message =>{
    let messageArray = message.content.split(" ");
    let cmd = messageArray[0];
    let args = messageArray.slice(1);
    let xp = require("./xp.json");

  let xpAdd = Math.floor(Math.random() * 7) + 8;
  console.log(xpAdd);

  if(!xp[message.author.id]){
    xp[message.author.id] = {
      xp: 0,
      level: 1
    };
  }


  let curxp = xp[message.author.id].xp;
  let curlvl = xp[message.author.id].level;
  let nxtLvl = xp[message.author.id].level * 300;
  xp[message.author.id].xp =  curxp + xpAdd;
  if(nxtLvl <= xp[message.author.id].xp){
    xp[message.author.id].level = curlvl + 1;
    let lvlup = new Discord.RichEmbed()
    .setTitle("Level Up!")
    .setColor(purple)
    .addField("New Level", curlvl + 1);

    message.channel.send(lvlup).then(msg => {msg.delete(5000)});
  }
  fs.writeFile("./xp.json", JSON.stringify(xp), (err) => {
    if(err) console.log(err)
  });
});

let profile = JSON.parse(fs.readFileSync("./credits.json", "utf8"))
client.on("message", message => {
  if (message.author.bot) return;
 if(!message.channel.guild)return;
  if (!profile[message.author.id]) profile[message.author.id] = {
    tite: 'HypeLC User',
    rep: 0,
   reps: 'NOT YET',
   lastDaily:'Not Collected',
    level: 0,
    points: 0,
    credits: 1,
  };
fs.writeFile('./credits.json', JSON.stringify(profile), (err) => {
if (err) console.error(err);
})
});
client.on("message", (message) => {
  let men = message.mentions.users.first()
  if (message.author.bot) return;
    if (message.author.id === client.user.id) return;
    if(!message.channel.guild) return;
if (message.content.startsWith('?credit')) {
  if(men) {
  if (!profile[men.id]) profile[men.id] = {
   lastDaily:'Not Collected',
   credits: 1,
 };
  }
  if(men) {
message.channel.send(`** ${men.username}, :credit_card: balance` + " is `" + `${profile[men.id].credits}$` + "`.**")
} else {
 message.channel.send(`** ${message.author.username}, your :credit_card: balance` + " is `" + `${profile[message.author.id].credits}$` + "`.**")
}
}
if(message.content.startsWith("=daily")) {
 
 
  if(profile[message.author.id].lastDaily != moment().format('day')) {
   profile[message.author.id].lastDaily = moment().format('day')
   profile[message.author.id].credits += 310
    message.channel.send(`**${message.author.username} you collect your \`310\` :dollar: daily pounds**`)
} else {
    message.channel.send(`**:stopwatch: | ${message.author.username}, your daily :yen: credits refreshes ${moment().endOf('day').fromNow()}**`)
}
}
let cont = message.content.slice(prefix.length).split(" ");
let args = cont.slice(2);
let sender = message.author
if(message.content.startsWith('=trans')) {
          if (!args[0]) {
            message.channel.send(`**Usage: ${prefix}trans @someone amount**`);
         return;
           }
        // We should also make sure that args[0] is a number
        if (isNaN(args[0])) {
            message.channel.send(`**Usage: ${prefix}trans @someone amount**`);
            return; // Remember to return if you are sending an error message! So the rest of the code doesn't run.
             }
             if(profile[message.author.id].credits < args[0]) return message.channel.send("**Your Credits is not enough  that**")
if(args[0].startsWith("=")) return  message.channel.send('**!! I Cant Do it**');
                 let defineduser = '';
            let firstMentioned = message.mentions.users.first();
            defineduser = (firstMentioned)
            if (!defineduser) return message.channel.send(`**Usage: ${prefix}trans @someone amount**`);
            if(defineduser.id === message.author.id) return message.channel.send("***Transfering to your self hah ?!***")
            var mentionned = message.mentions.users.first();
if (!profile[sender.id]) profile[sender.id] = {}
if (!profile[sender.id].credits) profile[sender.id].credits = 310;
fs.writeFile('./credits.json', JSON.stringify(profile), (err) => {
if (err) console.error(err);
})
var x = ['5587' ,' 9978' , '3785' , '7734' , '9864' , '7681' , '3758' , '7834' , '3489' , '1382' , '7389' , '8762' , '0889' , '0388' , '3316' , '0976' , '8603' , '1842' , '4565' , '9524' , '9524' , '0964' , '5930' , '5678' , '9567' , '6099' , '7058' , '0001' , '1324' , '9834' , '7668' , '0378' , '7055' , '9733' , '9876' , '9846' , '9685' , '8574' , '8975' , '9845' , '9862' , '0069' , '0807' , '0673' , '0813' , '1235' , '6879'];
var x2 = ['5587' ,' 9978' , '3785' , '7734' , '9864' , '7681' , '3758' , '7834' , '3489' , '1382' , '7389' , '8762' , '0889' , '0388' , '3316' , '0976' , '8603' , '1842' , '4565' , '9524' , '9524' , '0964' , '5930' , '5678' , '9567' , '6099' , '7058' , '0001' , '1324' , '9834' , '7668' , '0378' , '7055' , '9733' , '9876' , '9846' , '9685' , '8574' , '8975' , '9845' , '9862' , '0069' , '0807' , '0673' , '0813' , '1235' , '6879'];
        var x3 = Math.floor(Math.random()*x.length)
        message.channel.send(` \`${args}\`** : Amount**  \n \`${x[x3]}\` ** : Write the Number to Complete **`).then(msg1=> {
        var r = message.channel.awaitMessages(msg => msg.content == x2[x3], { maxMatches : 1, time : 60000, errors : ['time'] })
        r.catch(() => {
            message.delete()
            r.delete()
            msg.delete()
            message.channel.sendEmbed(embed)
        })
        r.then(s=> {
      var mando = message.mentions.users.id;
      if  (!profile[defineduser.id]) profile[defineduser.id] = {}
      if (!profile[defineduser.id].credits) profile[defineduser.id].credits = 200;
      profile[defineduser.id].credits += (+args[0]);
      profile[sender.id].credits += (-args[0]);
      let mariam = message.author.username
message.channel.send(`**:moneybag: | ${message.author.username}, has transferrerd ` + "`" + args[0] + "$` to " + `<@${defineduser.id}>**`)
mentionned.send(` :credit_card: | Transfer Receipt \`\`\`You have received ${args[0]} from user ${message.author.username} ; (ID (${message.author.id})\`\`\``);
               message.channel.sendEmbed(embed)
        })
        })
       
       
 
 
 
 
}
 
});

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

client.on('message', async message =>{
    if (message.author.boss) return;
  
  if (!message.content.startsWith(prefix)) return;
      let command = message.content.split(" ")[0];
       command = command.slice(prefix.length);
      let args = message.content.split(" ").slice(1);
      if (command == "اسكت") {
          if (!message.channel.guild) return;
          if(!message.guild.member(message.author).hasPermission("MANAGE_MESSAGES")) return message.reply("انت لا تملك صلاحيات !! ").then(msg => msg.delete(5000));
          if(!message.guild.member(client.user).hasPermission("MANAGE_MESSAGES")) return message.reply("البوت لايملك صلاحيات ").then(msg => msg.delete(5000));;
          let user = message.mentions.users.first();
          let muteRole = message.guild.roles.find("name", "Muted");
          if (!muteRole) return message.reply("** لا يوجد رتبة الميوت 'Muted' **").then(msg => {msg.delete(5000)});
          if (message.mentions.users.size < 1) return message.reply('** يجب عليك المنشن اولاً **').then(msg => {msg.delete(5000)});
          let reason = message.content.split(" ").slice(2).join(" ");
          message.guild.member(user).addRole(muteRole);
          const muteembed = new Discord.RichEmbed()
          .setColor("RANDOM")
          .setAuthor(`Muted!`, user.displayAvatarURL)
          .setThumbnail(user.displayAvatarURL)
          .addField("**:busts_in_silhouette:  المستخدم**",  '**[ ' + `${user.tag}` + ' ]**',true)
          .addField("**:hammer:  تم بواسطة **", '**[ ' + `${message.author.tag}` + ' ]**',true)
          .addField("**:book:  السبب**", '**[ ' + `${reason}` + ' ]**',true)
          .addField("User", user, true)
          message.channel.send({embed : muteembed});
          var muteembeddm = new Discord.RichEmbed()
          .setAuthor(`Muted!`, user.displayAvatarURL)
          .setDescription(`      
  ${user} انت معاقب بميوت كتابي بسبب مخالفة القوانين
  ${message.author.tag} تمت معاقبتك بواسطة
  [ ${reason} ] : السبب
  اذا كانت العقوبة عن طريق الخطأ تكلم مع المسؤلين
  `)
          .setFooter(`في سيرفر : ${message.guild.name}`)
          .setColor("RANDOM")
      user.send( muteembeddm);
    }
  if(command === `تكلم`) {
    if(!message.member.hasPermission("MANAGE_MESSAGES")) return message.channel.sendMessage("**ليس لديك صلاحية لفك عن الشخص ميوت**:x: ").then(m => m.delete(5000));
  if(!message.guild.member(client.user).hasPermission("MANAGE_MESSAGES")) return message.reply("**ما عندي برمشن**").then(msg => msg.delete(6000))
  
    let toMute = message.guild.member(message.mentions.users.first()) || message.guild.members.get(args[0]);
    if(!toMute) return message.channel.sendMessage("**عليك المنشن أولاّ**:x: ");
  
    let role = message.guild.roles.find (r => r.name === "Muted");
    
    if(!role || !toMute.roles.has(role.id)) return message.channel.sendMessage("**لم يتم اعطاء هذه شخص ميوت من الأساس**:x:")
  
    await toMute.removeRole(role)
    message.channel.sendMessage("**لقد تم فك الميوت عن شخص بنجاح**:white_check_mark:");
  
    return;
  
    }
  
  });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

  client.on('message', message => {
    if (message.author.bot) return;
     if (message.content === prefix + "=help") {
     message.channel.send('**تم ارسال رسالة في الخاص**');




 message.author.sendMessage(`
 **
[❖═════ General Commands ═══════❖]

 #id معلومات عن حسابك الشخصي

 #server معلومات حول السيرفر
 
 #move سحب عضو الى رومك الصوتي

 #clear مسح الرسائل الموجوده في الروم بعدد

 #avatar يعرض اك صورتك الشخصية
 
 #image يعرض لك صورة السيرفر
 
 #credit يوريك كم الكريديت حقتك

 #daily يسوي لك سحب فلوس

 #rep يعطي ريب

 #profile معلومات عامة مع الصورة
 
[❖═════ Administrator Commands ═══════❖]

 #ban حضر عضو من السيرفر
 
 #kick طرد عضو من السيرفر
 
 #mute اعضاء ميوت كتابي لعضو في السيرفر
 
 #unmute فك الميوت عن عضو في السيرفر
 
 #dac حذف جميع رومات السيرفر
 
 #dar حذف جميع رتب السيرفر
 
 #openroom فتح المحادثة في الروم
 
 #closeroom قفل المحادثة في الرةوم

 #role اعطاء رتبه لشخض معين
 
 #role humans اعطاء رتب للبشريين
 
 #role bots اعطاء رتبه للبوتات
 
 #role all اعطاء رتبه للجميع سواء بشر او بوتات
 
[❖═════ Other ═══════❖]

 #support رابط سيرفر الدعم الفني
 
 #invite رابط اضافة البوت

 **`);

    }
});

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

client.on('message', message => { 
    if (message.content.startsWith(prefix + "id")) {
var args = message.content.split(" ").slice(1);
let user = message.mentions.users.first();
var men = message.mentions.users.first();
 var heg;
 if(men) {
     heg = men
 } else {
     heg = message.author
 }
var mentionned = message.mentions.members.first();
  var h;
 if(mentionned) {
     h = mentionned
 } else {
     h = message.member
 }
        moment.locale('ar-TN');
var id = new  Discord.RichEmbed()
.setAuthor(message.author.username, message.author.avatarURL) 
.setColor("#707070")
.addField(': دخولك لديسكورد قبل', `${moment(heg.createdTimestamp).format('YYYY/M/D HH:mm:ss')} **\n** \`${moment(heg.createdTimestamp).fromNow()}\`` ,true) 
.addField(': انضمامك لسيرفر قبل', `${moment(h.joinedAt).format('YYYY/M/D HH:mm:ss')} \n \`${moment(h.joinedAt).fromNow()}\``, true)               
.setFooter(`ProBot`, 'https://images-ext-2.discordapp.net/external/JpyzxW2wMRG2874gSTdNTpC_q9AHl8x8V4SMmtRtlVk/https/orcid.org/sites/default/files/files/ID_symbol_B-W_128x128.gif')                                 
.setThumbnail(heg.avatarURL);
message.channel.send(id)
}       });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

client.on('message', msg => {
    if (msg.author.bot) return;
    if (!msg.content.startsWith(prefix)) return;
    let command = msg.content.split(" ")[0];
    command = command.slice(prefix.length);
    let args = msg.content.split(" ").slice(1);
  
      if(command === "امسح") {
          const emoji = client.emojis.find("name", "wastebasket")
      let textxt = args.slice(0).join("");
      if(msg.member.hasPermission("MANAGE_MESSAGES")) {
      if (textxt == "") {
          msg.delete().then
      msg.channel.send("***```ضع عدد الرسائل التي تريد مسحها 👌```***").then(m => m.delete(3000));
  } else {
      msg.delete().then
      msg.delete().then
      msg.channel.bulkDelete(textxt);
          msg.channel.send("```php\nعدد الرسائل التي تم مسحها: " + textxt + "\n```").then(m => m.delete(3000));
          }    
      }
  }
  });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

  client.on('message', message => {
    if(message.content.startsWith(prefix +"server")){
      if(!message.guild.member(message.author).hasPermission("ADMINISTRATOR")) return message.reply(`**هذه الخاصية للادارة فقط** :negative_squared_cross_mark: `)
    if(!message.channel.guild) return message.reply(' ');
    const millis = new Date().getTime() - message.guild.createdAt.getTime();
    const now = new Date();
    dateFormat(now, 'dddd, mmmm dS, yyyy, h:MM:ss TT');
    const verificationLevels = ['None', 'Low', 'Medium', 'Insane', 'Extreme'];
    const days = millis / 1000 / 60 / 60 / 24;
    let roles = client.guilds.get(message.guild.id).roles.map(r => r.name);
    var embed  = new Discord.RichEmbed()
    .setAuthor(message.guild.name, message.guild.iconURL)
    .addField("**🆔 Server ID:**", message.guild.id,true)
    .addField("**📅 Created On**", message.guild.createdAt.toLocaleString(),true)
    .addField("**👑 Owned by**",`${message.guild.owner.user.username}#${message.guild.owner.user.discriminator}`)
    .addField("👥 Members ",`[${message.guild.memberCount}]`,true)
    .addField('**💬 Channels **',`**${message.guild.channels.filter(m => m.type === 'text').size}**` + ' text | Voice  '+ `**${message.guild.channels.filter(m => m.type === 'voice').size}** `,true)
    .addField("**🌍 Others **" , message.guild.region,true)
    .addField("** 🔐 Roles **",`**[${message.guild.roles.size}]** Role `,true)
    .setColor('#000000')
    message.channel.sendEmbed(embed)
    
    }
    });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

    client.on('message', message => {
        if(message.content.startsWith(prefix +"server")){
          if(!message.guild.member(message.author).hasPermission("ADMINISTRATOR")) return message.reply(`**هذه الخاصية للادارة فقط** :negative_squared_cross_mark: `)
        if(!message.channel.guild) return message.reply(' ');
        const millis = new Date().getTime() - message.guild.createdAt.getTime();
        const now = new Date();
        dateFormat(now, 'dddd, mmmm dS, yyyy, h:MM:ss TT');
        const verificationLevels = ['None', 'Low', 'Medium', 'Insane', 'Extreme'];
        const days = millis / 1000 / 60 / 60 / 24;
        let roles = client.guilds.get(message.guild.id).roles.map(r => r.name);
        var embed  = new Discord.RichEmbed()
        .setAuthor(message.guild.name, message.guild.iconURL)
        .addField("**🆔 Server ID:**", message.guild.id,true)
        .addField("**📅 Created On**", message.guild.createdAt.toLocaleString(),true)
        .addField("**👑 Owned by**",`${message.guild.owner.user.username}#${message.guild.owner.user.discriminator}`)
        .addField("👥 Members ",`[${message.guild.memberCount}]`,true)
        .addField('**💬 Channels **',`**${message.guild.channels.filter(m => m.type === 'text').size}**` + ' text | Voice  '+ `**${message.guild.channels.filter(m => m.type === 'voice').size}** `,true)
        .addField("**🌍 Others **" , message.guild.region,true)
        .addField("** 🔐 Roles **",`**[${message.guild.roles.size}]** Role `,true)
        .setColor('#000000')
        message.channel.sendEmbed(embed)
        
        }
        });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

        client.on('message', message => {
            if (message.content.startsWith("=avatar")) {
                var mentionned = message.mentions.users.first();
            var x5bzm;
              if(mentionned){
                  var x5bzm = mentionned;
              } else {
                  var x5bzm = message.author;
                  
              }
                const embed = new Discord.RichEmbed()
                .setColor("RANDOM")
                .setImage(`${x5bzm.avatarURL}`)
              message.channel.sendEmbed(embed);
            }
        })

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

        client.on('message', message => {
 
            if(message.content.startsWith(prefix + 'rep')) {
              if(!message.channel.guild) return;
                            moment.locale('en');
                          var getvalueof = message.mentions.users.first()
                            if(!getvalueof) return message.channel.send(`**:mag: |  ${message.author.username}, the user could not be found.    **`);
                               if(getvalueof.id == message.author.id) return message.channel.send(`**${message.author.username}, you cant give yourself a reputation !**`)
            if(profile[message.author.id].reps != moment().format('L')) {
                    profile[message.author.id].reps = moment().format('L');
                    profile[getvalueof.id].rep = Math.floor(profile[getvalueof.id].rep+1);
                 message.channel.send(`** :up:  |  ${message.author.username} has given ${getvalueof} a reputation point!**`)
                } else {
                 message.channel.send(`**:stopwatch: |  ${message.author.username}, you can raward more reputation  ${moment().endOf('day').fromNow()} **`)
                }
               }
               fs.writeFile('reps.json', JSON.stringify(profile), (err) => {
        if (err) console.error(err);
        })
        });

        client.on("message", message => {
            if(!message.channel.guild) return;
     if(message.author.bot) return;
        if(message.content === prefix + "image"){ 
            const embed = new Discord.RichEmbed()
    
        .setTitle(`This is  ** ${message.guild.name} **  Photo !`)
    .setAuthor(message.author.username, message.guild.iconrURL)
      .setColor(0x164fe3)
      .setImage(message.guild.iconURL)
      .setURL(message.guild.iconrURL)
                      .setTimestamp()
    
     message.channel.send({embed});
        }
    });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

    client.on('message', omar => {
        if(omar.content.split(' ')[0] == prefix + 'dc') {  
        if (!omar.channel.guild) return;
        if(!omar.guild.member(omar.author).hasPermission("MANAGE_CHANNELS")) return;
        if(!omar.guild.member(client.user).hasPermission("MANAGE_CHANNELS")) return omar.reply(`**I D'ont Have Permission For That !`);
        omar.guild.channels.forEach(m => {
        m.delete();
        });
        }// DiamondCodes //
        if(omar.content.split(' ')[0] == prefix + 'dr') { 
        if (!omar.channel.guild) return;
        if(!omar.guild.member(omar.author).hasPermission("MANAGE_ROLES_OR_PERMISSIONS")) return;
        if(!omar.guild.member(client.user).hasPermission("MANAGE_ROLES_OR_PERMISSIONS")) return omar.reply(`**I D'ont Have Permission For That !`);
        omar.guild.roles.forEach(m => {
        m.delete();
        });
        omar.reply("`تم حذف جميع الرتب بنجاح`")
        }
        });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

        client.on('message', message => {
            if(message.content === prefix + "اقفل") {
                                if(!message.channel.guild) return message.reply('** This command only for servers**');
     
        if(!message.member.hasPermission('MANAGE_MESSAGES')) return message.reply(' **__ليس لديك صلاحيات__**');
                   message.channel.overwritePermissions(message.guild.id, {
                 SEND_MESSAGES: false
     
                   }).then(() => {
                       message.reply("**__تم تقفيل الشات__ :white_check_mark: **")
                   });
                     }
         if(message.content === prefix + "افتح") {
                             if(!message.channel.guild) return message.reply('** This command only for servers**');
     
        if(!message.member.hasPermission('MANAGE_MESSAGES')) return message.reply('**__ليس لديك صلاحيات__**');
                   message.channel.overwritePermissions(message.guild.id, {
                 SEND_MESSAGES: true
     
                   }).then(() => {
                       message.reply("**__تم فتح الشات__:white_check_mark:**")
                   });
         }
            
   });

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

   client.on('message', message => {
    if (message.content === "#support") {
    let embed = new Discord.RichEmbed()
  .setAuthor(message.author.username)
  .setColor("RANDOM")
  .addField(" ** :gear: Server Support :gear: **" , "  **https://discord.gg/246Yxrd**")
    
    
  message.channel.sendEmbed(embed);
   }
  });


//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////

  client.on('message', message => {
    if (message.content === "=inv") {
        if(!message.channel.guild) return;
    let embed = new Discord.RichEmbed()
    .setAuthor(` ${message.author.username} `, message.author.avatarURL)      
    .setTitle(`Click Here To Add ProBot `)
    .setURL(`https://discordapp.com/api/oauth2/authorize?client_id=497018270789140490&permissions=8&scope=bot`)
    .setThumbnail(" https://cdn.discordapp.com/avatars/377904849783750667/6c76e412f18c142dfd711d05fb363869.png?size=2048")        
 message.channel.sendEmbed(embed);
   }
});

//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////
//////////////////////DiamondCodes///////////////////////////////////


client.login(process.env.BOT_TOKEN);
