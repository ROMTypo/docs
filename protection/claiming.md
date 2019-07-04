# Claiming

You can protect your land from unauthorized building by right clicking two corners with a golden shovel.
Each claim claims from bedrock to build limit, so you don't need to worry about height.
You are restricted by how many "blocks" you can claim, and the remaining amount is displayed on the sidebar.
You can buy more with the in-game currency with `/buyclaimblocks` and sell with `/sellclaimblocks` you can buy
one claim block for $10 and sell it for $8 each.

## Trusting people

If you don't trust anyone, only you will have access to your chests and redstone contraptions.
You can trust everyone using `public` as the username (e.g. `/accesstrust public`)

* Access trust `/accesstrust Username`

Access trust allows for levers and other redstone contraptions to be used in your claim

* Container trust `/containertrust Username`

Container trust allows for chests and furnaces to be used in your claim

* Full trust `/trust Username`

Full trust allows building and breaking blocks

## Subdividing claims

You can enter subdivide mode with `/subdivideclaim` while holding a golden shovel. This will allow you to make
subclaims inside your claims and trust players only in that subclaim. This is useful for building towns or allowing
public access to a specific chest. Subdivded claims are shown with an iron block border, compared to golden borders
of full claims. Trusting in subclaims works similarly to whole claims, except that a player trusted in the full
claim will also have their trust permissions in subclaims.

If you wanted to have a town smeltery without allowing people to break blocks there, but you also want them to be
able to break claims in their own subclaim, you can `/containertrust` them in the whole claim and `/trust` them
in their subclaim.

Keep in mind that trusted users can trust other users. You can remove *all* trusts using `/untrust all`
