# LWC

Most players will only need to know the basic functions of LWC. That is, protecting blocks and managing said protections.

There are 3 protection types in LWC:

<table>

<tr>
	<td> Public </td>
	<td>
		Anyone can access the protection, but no one can protect it for themselves. Mainly useful for community chests that store items for anyone to use
	</td>
</tr>

<tr>
	<td> Private </td>
	<td>
		By default, only you can access the protection. You can also add other players and groups to the protection so that they, too can access it. So your chest and doors can only let in your close friends and those you choose to add to it.
	</td>
</tr>

<tr>
	<td> Password </td>
	<td>
		The protection has a set password and you need to enter it each time you login. This can of course be shared with other players -- they will be able to access the protection until they log out (after that they will need to re enter it)
	</td>
</tr>

</table>

**Note:** The server will protect blocks to 'Private' when you place them. If you want a password chest and it's already protected, simply use the command `/cremove` and then hit your chest to remove the protection first.

Ok great, but how do I create a protection?

<center> <img src="https://puu.sh/I4BW.png"> </center>

Is what you would use for a basic private protection. Password protection is the same deal.

<center> <img src="https://puu.sh/I4EJ.png"> </center>

Now pay attention to what happens in the chat box once you hit enter:

<center> <img src="https://puu.sh/I4EQ.png"> </center>

Hit your chest and you'll have a protection!

<center> <img src="https://puu.sh/I4Fx.png"> </center>

## Viewing protection info

As a user or owner of a protection, you can use `/cinfo` on a protection which will let you view information on a protection. An example of this command is below.

<center> <img src="https://puu.sh/I4Wl.png"> </center>

Or a private protection, which you own:

<center> <img src="https://puu.sh/I4Xb.png"> </center>

You'll probably notice this has an 'Access Control List' (or ACL for short) under it. This is covered more in the next section.

## Private protections - ACLs

Private protections can have various 'ACLs', or who exactly can access the protection. The owner is considered just that - the owner - and cannot be removed from the protection, only by using `/cremove` on it.

You can add (and remove) ACLs from a protection both when creating it and after you create it. If you wanted to add your friends at the same time you used `/cprivate` you'd use something like: `/cprivate player1 player2 ..` and then hit your protection. You'll get something like:

<center> <img src="https://puu.sh/I51n.png"> </center>

Adding ACLs afterwards is done with `/cmodify`

<center> <img src="https://puu.sh/I51T.png"> -> <img src="https://puu.sh/I521.png"> </center>

Removing ACLs / players from a protection is as easy as prepending `-`

<center> <img src="https://puu.sh/I53i.png"> -> <img src="https://puu.sh/I53m.png"> </center>

### ACL Admins

You can grant an ACL entity (a player or group) "admin" access to the protection. This means that they can use `/cmodify` (but not `/cremove`) to edit the protection. They will NOT be able to remove the owner (as the owner is outside the bounds of ACL) and thus can only add or remove other players.

This is done by prepending `@`

<center> <img src="https://puu.sh/I55Q.png"> -> <img src="https://puu.sh/I55z.png"> </center>

Additionally, admins will show up in `/cinfo` as an admin.

<center> <img src="https://puu.sh/I56l.png"> </center>

Finally, they can be removed just like any other group/player by prepending `-`

<center> <img src="https://puu.sh/I56H.png"> -> <img src="https://puu.sh/I56V.png"> </center>

<small>Edited from the [official wiki](https://github.com/Tsuser1/Modern-LWC/wiki/Getting-Started) to fit the server more</small>
