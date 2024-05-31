In Typescript, any value can be assigned to the unknown type,
but without a type assertion, unknown can't be
assigned to anything but itself and the any type. 
Similarly, no operations on a value 
with its type set as unknown are allowed 
without first asserting or restricting 
it to a more precise type.
