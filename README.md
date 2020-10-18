Installing ruby:
``` 
   sudo apt-get install ruby-full build-essential zlib1g-dev  
   echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc  
   echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc  
   echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc  
   source ~/.bashrc
``` 
Installing jekyll dependencies:
``` 
   gem install jekyll bundler
   bundle exec jekyll serve
   bundle install
``` 
Local host startup:
``` 
bundle exec jekyll serve
``` 
