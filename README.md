# Loose-Class
C++ class to provide a loose (weak) typed variable.
Provides a class that can represent a variable as either ALPHA (std::string) or NUMERIC (double) and permit conversion from one type to the other at run time, much like in languages such as BASIC. Loose variables can also be flagged as BLANK or NA (non applicable).

eg.

/// Initiation.

LOOSE_CLASS MyVariable( "Hello World" ); /// Initialise as ALPHA.

/// Change type at run time.

MyVariable = 123; /// Change to a NUMERIC.

/// Getters (of which there are many)

MyVariable.GetAsString(); /// Return (std::string)"123"

MyVariable.GetAsDouble(); /// Return (double)123.0

MyVariable.GetAsInt(); /// Return (int)123
