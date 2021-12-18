# monadic_history_map
A mapping of all history.

It is done in the monadic style. Meaning that each directory is one abstraction level down, branching into details.
Each dictionary contains several files:
 - NAME.monad : Where name is the description of the monad such as Medival or French Revolution. Contains the definition of the monad.
		- Level of abstraction: An identification number of what levelof abstraction this monad is about.
 - paths : Describes the monads relation to other monads


## About

Each monad describes a particular geolocation, defined in it's level of abstraction, (could be Europe, World, France or Stockholm, or Nacka, there's no limit.) . We prefer not to use the idea of geolocation, rather material composition.

Each monad defines a time-span in its .monad file. And this time-span must concur to it's childs. In ez-mode it's okay not to.

The path-file specifies for instance, continuations of history between monads. Theese paths can go to other directories. Paths should prefferably link to other monads of similar abstraction levels, but it's not required.

While some countries develop rather independent from other countries, they will also inflict on others, for such interaction we use paths.

## Do's and Dont's

Do not define a monad with the purpuse of spanning thrugh a set timespan such as 1789.monad. Instead declare it as a particular event that occured at that time, or perhaps multiple. French revolution.



## The general design and standards.
Theese are further described in the monad files for their monads. Look at each monad's standard-section.
