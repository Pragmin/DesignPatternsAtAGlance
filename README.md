Getting to know design patterns, concisely! **This repo is still a draft**.

# Factory
A factory creates an object complying with a given interface.

**Real life**: You call for a Taxi. Because Joe is on vacations, Bob is coming. You don't care. But it was insightful not to call for Joe directly!

# Decorator
A decorator wraps an object. It maintains its interface but changes its behavior.

**Real life**: We sell a dessert with some extras on it.  
![Dessert making](img/decorator_dessert_making.png)

**Software**:
```
Stream stream1 = new StreamToFile("my-file.txt");
Stream stream2 = new StreamCompressor(stream1);
Stream stream3 = new StreamEncrypter(stream2);
```
**Decorator vs inheritance**: in the simple previous example, there is no need to define a StreamCompressorEncrypter implementation.

# Proxy
A proxy wraps an object that is remote from the  point of view of the program.

# Adapter
An adapter wraps an object. it changes its interface to comply with another interface. It does not change the object behavior.
**Real life**: A 2.5mm to 3.5mm headphone adapter

#Visitor
A visitor externalize and centralize some operational logic from classes to another external class.  
**Real life**: An online shopping cart computing total price with taxes by itself, instead of retrieve all precomputed price from items.

**Software**: Debug and display code can be externalized from classes in an other new class.

# Observer
An observable object send notifications to registered observers.  
**Real life**: When in an auction, a bidder raise his hand and the auctioneer accept the new bid price, all bidders know it.

**Software**:
Button b = new Button("button");
b.addActionListener(this);

# The chain of responsability
**Real life**: 

# TODO
Mediator, Publisher/subscriber
