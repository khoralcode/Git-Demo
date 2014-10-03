#Demo Git Repository

This is the forst line of this repo.

## Ipsum Below

I receive the error: "Cannot find protocol declaration for 'NSComparisonMethods' ".

Shouldn't the NSComparisonMethods protocol exist within Foundation.h, or is that a protocol that I have to write myself? I've written a custom protocol with the same title and included methods, which I found when looking up the protocol. After importing that custom protocol, I was able to make use of it within my custom Fraction class. 

Am I doing something wrong? I was under the impression that I could simply list a protocol and make a class conform to its methods... I'm very confused! Any thoughts or tips would be greatly appreciated.

Thanks for chiming in, Brian.

I'm still having a little bit of trouble with even your code. For whatever reason, the NSCompareMethods that do lesser/greater do not work. 

I copied your code over and I'm still having problems with even your code. I must be doing something wrong in terms of how it's comparing lesser or greater. Did you define your isLessThan or isGreaterThan code? Or is your Fraction+NSComparisonMethods.m empty? 

For example, when running your code, I get the following output: