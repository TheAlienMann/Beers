## Beers, <br/><br/>An application that fetches data from punkapi beers, presents them in a list (or a Table or CollectionViewController, haven't decided yet which one!).

I am planning for follow a modular clean architecture for it, but before moving on "so fast", let's have a little bit `thought process` per say.

### Thought process

For a modular architect in an iOS project, in a high level, you have two options, one using the traditional Frameworks, the other one would be Swift Packages, which each one comes with it's own pros and cons. <br/> One of the main purpose of having a modular architect, obviously, is to have a team of at least two people to work on the project and proceed with their task without making any obstacle for one and another.<br/> For the sake of this project (obviously not bothering with details on the pros & cons, for the moment, but, if interested, I have another project that I have listed a few details on this matter that you can find it [here](https://github.com/TheAlienMann/EssentialApp)), I'd like to go on with the traditional Frameworks.<br/><br/>
Moving on <br/><br/>




punk api beers endpoint:

`
https://api.punkapi.com/v2/beers
`
