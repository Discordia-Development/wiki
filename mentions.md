<!-- TITLE: Mentions -->
<!-- SUBTITLE: Notify users directly -->

Mentions are a way to directly notify a user, multiple users or roles in messages. The main purpose of them is to be able to get someone into a channel or showing you're talking to them specifically. You can mention users or roles using `@name`.

# Mentioning users
When mentioning a user directly, they will receive a notification and the message will be highlighted for them. There's no permissions to mention users individually. To mention an user in the client or web app you can start typing out their name, having a selection menu pop up or right click the user and select "Mention". On the mobile application you can just press on the user's name or profile picture and they will be mentioned in the text box.

# Mentioning roles
When mentioning a role, every user that has access to the channel will get a notification and the channel will be highlighted as if mentioned directly. To allow a role to be mentioned by anyone, enable it for that role under Server settings > Roles > Allow anyone to @mention this role. Many server owners like to enable this for a short time when wanting to mention all users of a role once and then disable it again when making announcements to a specific role.

# @everyone and @here
Using `@everyone` and `@here` allows for mentioning every member with and without roles. The difference between the two is that `@everyone` mentions even offline users while `@here` only mentions users who are online and aren't idle at the moment.

# Mentions using IDs
You can also directly mention an user or a role through the ID. The client replaces `@role` or `@username#discrim` with `<@ID>` and `<@&ID>` (respectively) and vice versa automatically. The reason this is used is because names change while IDs don't. The client not displaying mentions as the user- or role name can be achieved by escaping the mention. This can be done by typing `\@name#discrim` or `\@role` and will display the ID but still tag the user. Mentioning users by their ID is commonly used by bots.