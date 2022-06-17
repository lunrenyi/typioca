# typioca
Minimal, terminal based typing speed tester.


> **Tapioca** (/ˌtæpiˈoʊkə/) is a starch extracted from the storage roots of the cassava plant. Pearl tapioca is a common ingredient in Asian desserts...and sweet drinks such as **bubble tea**.

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/bloznelis/typioca)
---

![](https://github.com/bloznelis/typioca/blob/master/img/typioca.gif)

## Features
  * Time or word/sentence count based typing speed tests
  * Proper WPM results based on https://www.speedtypingonline.com/typing-equations
  * Multiple word/sentence lists made out of classical books to spice your test up
  * Cursor aware word lines
  * Interactive menu
  * ctrl+w support ;)
  * SSH server `typioca serve`

## Installation
### AUR
`yay -S typioca-git`

### Homebrew
1. `brew tap bloznelis/tap`
2. `brew install typioca`

### Go
`go install github.com/bloznelis/typioca@latest`<br>
*This will install typioca in $GOBIN, which defaults to $GOPATH/bin or $HOME/go/bin if the GOPATH environment variable is not set.*

### Building from source
  1. Checkout the code
  2. `make build`
  3. `./execs/typioca`

#### Prerequisites
  * `make`
  * `go`

---
![full-menu-cropped](https://user-images.githubusercontent.com/33397865/172426966-d1295987-4df3-4681-a651-b01f3f80be42.png)
![full-test-cropped](https://user-images.githubusercontent.com/33397865/172427152-b71979e4-8c67-4427-98e0-116c6518071f.png)
![full-results-cropped](https://user-images.githubusercontent.com/33397865/172427164-b19f1bb5-43a7-47d6-a833-c343e519f447.png)




### Acknowledgments
Built with [bubbletea](https://github.com/charmbracelet/bubbletea)

🧋
