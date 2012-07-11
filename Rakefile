require "rubygems"

desc "rebuild .MacOSX/environment.plist"
task :sync_path do
  `defaults write $HOME/.MacOSX/environment PATH "$PATH"`
  `cp ~/.MacOSX/environment.plist ~/projects/dotfiles/.MacOSX/`
end
