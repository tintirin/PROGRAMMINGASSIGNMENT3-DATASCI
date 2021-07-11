#this function shows how to properly use sandsquarecube
#show me how u hashtag
#tinriririn

createCacheMatrix <- function(x=matrix()){
      p<- NULL
      set<- function (b){
            a <<- b
            p <<- NULL
      }
      get <- function() a
      setP <- function(compute) P<<- compute
      getP<- function() (p)
      list(set = set, get = get, setP=setP,getP=getP
}

cacheSolve  <- function(a, ...) {
      p <- x$getP()
      if (!is null (p)){
            message ("towards cached data")
            return(p)
      }
      data <- x$get()
      p<- solve(data,...)
      a$setP(p)
      p
      ##matrix return is the opposite of "a"
}
