# ********************************************************************************* #
#                                                                                   #
#                                                      :::     ::: :::     :::      #
#    How_to.txt                                       :+:    :+:  :+:     +:+       #
#                                                    +:+   +:+   +:+     +:+        #
#    By: nxwbtk <bunthakan.s@ku.th>                 +#+  +:+    +#+     +#+         #
#                                                  +#+ #+#     +#+     +#+          #
#    Created: 2022/07/03 19:18:49 by nxwbtk       #+#   #+#   +#+     +#+           #
#    Updated: 2022/07/03 19:42:20 by nxwbtk      ###     ###   ########.th          #
#                                                                                   #
# ********************************************************************************* #

1. Enter the command below in your terminal(wsl):
	git clone https://github.com/42Paris/42header; mkdir ~/.vim; cp -r 42header/plugin ~/.vim; rm -rf 42header
2. Go to "~/.vim/plugin" and Replace the file in this repository to the plugin folder
3. Vim ~/.vimrc and place this command:
	set autoindent
	set smartindent
	set background=dark
	set tabstop=4
	set shiftwidth=4
	set backspace=indent,eol,start
	syntax on
	set mouse=a
	let g:user42 = 'YourUsername'
	let g:mail42 = 'YourEmail'
4. Change your Username and Your Email
5. Enjoy!!!

Cr. 42.fr,alexandregv,ptippaya
