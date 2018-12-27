# Qt 5.5

Just the removed [qt55](https://github.com/Homebrew/homebrew-core/pull/32565), which required by [capybara-webkit](https://github.com/thoughtbot/capybara-webkit), at least for me...

## Installation

```bash
git clone https://github.com/Eric-Guo/homebrew-qt55
cp Formula/qt\@5.5.rb /usr/local/Homebrew/Library/Taps/homebrew/homebrew-core/Formula/
brew install qt@5.5
```

## Remove

Just remove the file you copy to the homebrew-core.

## Note

Must install from bottle, if you try compile from source, it will failed, that's why the installation method is different from a normal brew tap.

## How to install capybara-webkit

```bash
export PATH="/usr/local/opt/qt@5.5/bin:$PATH"
gem install capybara-webkit
```
