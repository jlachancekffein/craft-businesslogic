# Business Logic plugin template for Craft CMS

_It's a plugin about nothing..._

## Uhh... what?

When building a Craft website for your clients, you may find that you occasionally need to write some quick PHP to solve a problem. The good news... Craft lets you write any PHP you want via a custom plugin! The bad news... Putting together a plugin just to write some simple business logic can be kind of a pain, and the effort often feels like overkill.

## What do you mean by "business logic"?

The term **business logic** is common in the software world... It basically means, "any processing logic which is unique to this specific company".

It's a boring topic, so [I'll let Wikipedia explain it...](http://en.wikipedia.org/wiki/Business_logic)

## So really, what does this plugin do?

It does whatever you want it to do. It's a very simple **template**, designed to give you the basic tools you need to create a quick PHP-based interaction with the rest of your website. What you write inside this plugin is entirely up to you, and we expect that every website will have its own unique implementation. Go nuts!

## What's included?

### Variables

If you just need to pull some data into your template, or want to run a quick process before handing an array (or string, or whatever) back to your template, then variables might be the way to go!

### Controllers

You might need a submitted form to do something special, or you might have an AJAX call with some simple back-end logic to sort out. Putting that stuff into a controller will let you work your magic behind the scenes.

### Services

No serious plugin is complete without a services layer. When things start to get a little crazy with your business logic, try moving large chunks of it to the services file. And if you decide that you need to create any Records (or interact with the database at all), then you'll definitely want to put that logic into the services file!

## What _isn't_ included?

Field Types, Records, Models, Element Types... Basically anything that seems unnecessary for the vast majority of business logic needs. If you're capable of determining that your business logic requires something as complex as an Element Type, we figure that you're smart enough to know how to build it from scratch.

***

## Fork Me!

Think this template can be improved? Go ahead and fork it! Pull requests are welcome, just keep a few simple goals in mind...

 - This plugin is designed to be ultra **simple**!
 - Only the basic needs of business logic need to be met... If a developer requires something more complex, it's assumed that they are capable enough to add those features.
 - Documentation is important! The components of this plugin should explain what they do, so any Craft noob can figure out how to shove some quick PHP in there and be on their merry way.

Don't want to fork, but still want to make a suggestion? Feel free to leave your comments on [this "General Discussion" thread...](https://github.com/lindseydiloreto/craft-businesslogic/issues/1)

***

Thanks for checking it out! And feel free to also grab [our favorite plugin of all time...](https://github.com/mattstauffer/happybrad)