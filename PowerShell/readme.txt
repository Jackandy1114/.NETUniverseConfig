iwr -useb get.scoop.sh | iex
Install-Module oh-my-posh -Scope CurrentUser
Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module -Name PSFzf -RequiredVersion 2.0.0
Install-Module -Name posh-git -RequiredVersion 0.7.1	
Install-Module -Name z -RequiredVersion 1.1.9	

scoop install git
scoop install fzf
