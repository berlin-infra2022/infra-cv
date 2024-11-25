# Step.0 Dependency installation for using this repository
## Step. 1 Installing Homebrew on your mac OS => install 'brew' command
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
## Hit 'Enter' key => enter root password
## Step.2 Now, we need to echo Ruby runtime onto our mac OS environment
```bash
echo 'export PATH="/usr/homebrew/bin:$PATH"' >> ~/.zshrc
```

## Step.3 Apply the changes
```bash
source ~/.zshrc
```

## Step.4 Testing out 'brew' command
```bash
brew help
```

## Step.5 Testing out 'gem' command
```bash
gem --help
```

## Step.6 Installing Ruby runtime on your mac OS
## Please do NOT run as root...
```bash
brew install ruby
```

## Step.7 Install Ruby Env 
```bash
brew install rbenv
```

## Step.8 Initialize Ruby Env
```bash
rbenv init
```

## Step.9 Install Ruby ver. 3.0.0
```bash
sudo rbenv install 3.0.0
```

## If you mistyped Ruby ver. to be installed
## Force install to up-to-date version of Ruby
```bash
rvm install ruby --latest
```

## Step.7 Installing 'bundler' command to install dependencies for this repository
```bash
sudo gem install bundler:2.3.19
```
## Step.8 Make Ruby ver. 3.0.0 a Global Env
```bash
rbenv global 3.0.0
```

## Step.9 Ensure Ruby ver. >= 3.0.0
```bash
ruby -v
```
## This should show 'ruby 3.0.0p0 (datetime revision hashNumber) [arm64-darwin22]

## Step.10 Install required ruby gems for this repo
```bash
bundle install
```

## Step.11 Serve the site locally
```bash
bundle exec jekyll serve
```

## Step.12 Finally, visit this Ruby CV locally
## Navigate to http://localhost:4000

## Styling site

## Changing background-color for sections under your Icon
## _sass => skins => _ceramic.scss
## Changing background-color for your Icon section
## _sass => skins => _base.scss
## lookup background attribute inside css class .profile-container

<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

# Orbit
> This theme is designed by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/).
> Visit [her website](http://themes.3rdwavemedia.com/) for more themes.

I have made this into a Jekyll Theme. Checkout the live demo [here](https://online-cv.webjeda.com).

<table>
  <tr>
    <th>Desktop</th>
    <th>Mobile</th>
  </tr>
  <tr>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/desktop.png?raw=true" width="600"/>
    </td>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/mobile.png?raw=true" width="250"/>
    </td>
  </tr>
</table>

## Skins

There are 6 color schemes available:

| Blue | Turquoise | Green |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/blue.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/turquoise.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/green.jpg" width="300"/> |

| Berry | Orange | Ceramic |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/berry.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/orange.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/ceramic.jpg" width="300"/> |

## Credits

Thanks to [Nelson Estevão](https://github.com/nelsonmestevao) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=nelsonmestevao).

Thanks to [t-h-e(sfrost)](https://github.com/t-h-e) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=t-h-e).

Check out for more themes: [**Jekyll Themes**](http://jekyll-themes.com).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sharu725/online-cv&type=Date)](https://star-history.com/#sharu725/online-cv&Date)

