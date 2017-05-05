---
layout:     post
title:      "We're going Mobile!"
date:       2014-08-12 16:00:00
author:     "Yves Chiong"
---
<p>
    <object class="card-shadow"
            style="width: 100%; height: 480px"
            data="/img/posts/2014-08-12/multi-directional.swf">
    </object>
    <span class="caption text-muted">Multi-directional swipe prototype.</span>
</p>

WOAH WOAH WOAH! What's going on here? Could it be? MD is working on a new game? That's right folks (the one or two of you). This game is targeted towards mobile devices and we're considering to first release it on Android, but that's to worry about later.

So we're using Adobe AIR for cross-platform development. Since we're so familiar with ActionScript and Flash, we thought it'll be best to break into the mobile games market with a title made in Flash. This will probably be our last title in Flash because of Adobe's discontinued support for it and our undying will to migrate over to Unity or explore some other tools to begin real development.

So just a little explanation on this short demo of our upcoming game. Imagine Tetris blocks to be placed in this 5x5 board. The blocks that come up are randomized and you're supposed to try to fill the board with these blocks as full as you can. The red cells in the board means that you can't click on it and place a block there and the blue cells means you can. It's just a little confusing indication of what you can click and what you can't. Anyways, if you click and hold and a blue cell, you would notice that the tetrimino appears but with a black mark on one of the block's cells and that mark actually indicates where control of the block will be according to your mouse. So if you drag the block or your mouse to another cell on the board then the block follows with the mark following your mouse control which would control where the block goes.

Confusing, we know.

So maybe now the red and blue cells make sense? Red cells means you can't click or drag on those cells because the current block's shape won't allow it either because it'll be out of the board or it'll cover another block on the board. If you haven't noticed by now, you can swipe downwards, leftwards, rightwards on the white space and the board will fly away in that direction. This was intended to be a part of the game. We'll need to figure out a way to make this more intuitive. Going to have to spend some more time with planning and designs for now.

Thanks for reading!