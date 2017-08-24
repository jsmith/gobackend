# Lukabox
This is the backend RESTful API for Lukabox!

## Setup
1. Install [vod](https://github.com/jacsmith21/vod) & make sure it's in your path
2. Create the folder stc `src/github.com/jacsmith21` in your GOPATH
3. Clone this repository in the `jacsmith21` folder
4. Run:
```
$ go get github.com/go-chi/jwtauth
$ go get github.com/go-chi/render
$ go get github.com/go-chi/chi
$ go get github.com/Sirupsen/logrus
```
5. In the `jacsmith21` folder, run:
```
$ vod run main.go
```

## TODO
* Get box working!
* Create schema for everything
* Rename the stc package

## References
* https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1
* https://forum.golangbridge.org/t/comparing-the-structure-of-web-applications/1198/16

## Things I Need To Research
* Research schemas for golang
* Consistency stuff... how should one update fields in a database?
* More authentication stuff
