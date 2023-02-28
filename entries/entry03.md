# Entry 3
## 2/12/23

I continue to use melonJS and what I have made so far is a hold button in which if you hold Q it would make it low gravity
```js
  if (me.input.isKeyPressed("gravity")){
            this.body.setMaxVelocity(10, 30);
        }
        else {
            this.body.setMaxVelocity(10, 10);
        }
```

As shown from that code snippet I had used [isKeyPressed](https://melonjs.github.io/melonJS/docs/melonjs/input/isKeyPressed.html) which in this code snippet is apart of a conditional saying if that select key which in my case was Q which I binded and named it gravity. On top of that I had used [setMaxVelocity](https://melonjs.github.io/melonJS/docs/melonjs/Body.html) which in the parameters has x and y with x being how fast you go and y being how high you can jump and so I had increased the number which makes a higher distance being reached only if the key was pressed. All this was accomplished by scrolling through the documentation with a goal in mind. I had intially tried to make toggle using [keyStatus](https://melonjs.github.io/melonJS/docs/melonjs/input/keyStatus.html) but it is similar to isKeyPressed but the true and false booleans are key press down and up respectively. 


## EDP
I'll say I am currently at stage 2 as I have much more to learn about MelonJS as I managed to get to a hold key function but what if i wanted to make a toggle which I attempted and eventually work on complex stuff such as switching from a main menu to the actual game. 

## Skills
As for skills I used at this point were how to learn as the journey for my freedom project is to learn MelonJS which I am doing now and towards making the actual game in which I would probably learn things I wouldn't have seen other wise and the other skill is how to read as the documentation is what I had used to learn and for me to learn I would have read what I needed to find and see what it did.

## Future
For the future I still plan on learning MelonJS itself but on top of that I also want to learn how to use Krita and Tiled to make sprites and the stages in the future as it is a required part for my game.






[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)