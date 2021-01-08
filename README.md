# dapper-commands

> **Note**: For more support use [this server](https://discord.gg/6Q9hCqvWMn)

# Tag System

#### tag <tag name>
If a tag has a multiple space name type it as normal, though you still can use `""` if you want.
<hr>

#### tag create <tag name> <tag content>
If you wanna use more than one space in the name surround it with "", for example: `????tag create "dapper is cool" oh no dapper is cool`
<hr>

#### tag delete <tag name>
If a tag has a multiple space name type it as normal, though you still can use `""` if you want.
**YOU MUST** be the owner of the tag or have administrator to delete it.
<hr>

#### tag stats <tag name>
If a tag has a multiple space name type it as normal, though you still can use `""` if you want.
<hr>

#### tag random
Gets you a random tag

# Moderation

#### ban <user id | mention | name#tag> <reason < 512 characters>
<hr>

#### softban <user id | mention | name#tag> <reason < 512 characters>
*Bans then unbans to delete messages*
<hr>

#### ghostban <user id> <reason < 512 characters>
*Bans a user who isn't in your server*
<hr>
  
#### multiban <users>  <reason < 512 characters> **BORKEN RN, wouldnt recommend using lol. Fixing soontm**
*Bans a user who isn't in your server*
<hr>
  
#### mute <user id | mention | name#tag> <reason < 512 characters>
<hr>

#### mute role set <role id | mention | name>
<hr>

#### mute role update
<hr>

#### mute role create <name>
*Name defaults to "Muted"*
<hr>

#### unmute <user id | mention | name#tag> <reason < 512 characters>
<hr>

#### kick <user | mention | name#tag> <reason < 512 characters>
<hr>

#### warn <user id | mention | name#tag> <reason < 512 characters>
*Include --silent in your reason to **not** dm the user*
<hr>

#### warnings <user id | mention | name#tag> 
*view a users warnings*
<hr>

#### warn remove <case id>
*Remove a users warning*
<hr>
  
#### warn reason <case id> <new reason>

# Self roles

#### role add <role name | id>
<hr>

#### role remove <role name | id>
<hr>

#### iam <role name>
*Only gives roles in the server's self role list*
<hr>
  
#### iamn <role name>
*Removes a role the user has*
