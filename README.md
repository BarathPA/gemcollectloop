# gemcollectloop
#collecting in a straight path

var gemCounter = 0       //variable to count the number of gems
while gemCounter < 7 {   //while loop to collect gems until given amount, here 7
    moveForward()
    if isOnGem {
        collectGem()
        gemCounter = gemCounter + 1
    }
    if isBlocked {      //once path is blocked or character meets dead end, to turn and go back to old path
        turnLeft()
        turnLeft()
    }
    
}
