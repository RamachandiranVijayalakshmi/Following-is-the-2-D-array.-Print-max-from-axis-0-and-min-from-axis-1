## Following-is-the-2-D-array.-Print-max-from-axis-0-and-min-from-axis-1
## Sample code to check the details 
```sh
import numpy

print("Printing Original array")
sampleArray = numpy.array([[34,43,73],[82,22,12],[53,94,66]]) 
print (sampleArray)


minOfAxisOne = numpy.amin(sampleArray, 1) 
print("Printing amin Of Axis 1")
print(minOfAxisOne)

maxOfAxisOne = numpy.amax(sampleArray, 0) 
print("Printing amax Of Axis 0")
print(maxOfAxisOne)
```
## Example output
Printing Original array
[[34 43 73]
 [82 22 12]
 [53 94 66]]
Printing amin Of Axis 1
[34 12 53]
Printing amax Of Axis 0
[82 94 73]
