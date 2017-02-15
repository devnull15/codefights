/**
After becoming famous, CodeBots decided to move to a new building and live together. The building is represented by a rectangular matrix of rooms, each cell containing an integer - the price of the room. Some rooms are free (their cost is 0), but that's probably because they are haunted, so all the bots are afraid of them. That is why any room that is free or is located anywhere below a free room in the same column is not considered suitable for the bots.

Help the bots calculate the total price of all the rooms that are suitable for them.
**/

def matrixElementsSum(matrix):
    skipCols = []
    sum = 0
    for row in xrange(0,len(matrix)):
        for col in xrange(0,len(matrix[row])):
            if col not in skipCols:
                if matrix[row][col] is 0:
                    skipCols.append(col)
                else:
                    print "adding " + str(matrix[row][col])
                    sum += matrix[row][col]
    return sum
