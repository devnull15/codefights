import copy
def reverseOnDiagonals(matrix):
    ret = copy.deepcopy(matrix)
    for i in xrange(len(matrix)):
        temp = matrix[i][i]
        endIndex = -1 - i
        print matrix[i][i]
        ret[i][i] = matrix[endIndex][endIndex]
        ret[endIndex][endIndex] = temp
    for i in xrange(len(matrix)):
        endIndex = -1 - i
        temp = matrix[i][endIndex]
        print matrix[i][i]
        ret[i][endIndex] = matrix[endIndex][i]
        ret[endIndex][i] = temp
    return ret
