Getting to know design patterns, concisely! **This repo is still a draft**.

# Factory
A factory creates an object complying with a given interface.
**Real life**: You call for a Taxi. Because Joe is on vacations, Bob is coming. You don't care. But it was insightful not to call for Joe directly!

# Decorator
A decorator wraps an object. it maintains its interface but changes its behavior.
**Real life**: A wattmeter plugged in an electrical outlet.
**Software**:  no need to define what is compressing an encrypted 
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

# The chain of responsability
**Real life**: 

# TODO
Mediator, Observer, Publisher/subscriber, Visitor