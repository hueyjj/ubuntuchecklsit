# ubuntuchecklist
Software, configuration, scripts, and dotfiles checklist for new ubuntu install

Commands won't be provided, because they change over time. PPA's, curling into bash, etc.,
might not yield the same result one or two years from now. Also, better tools may have come
out by then.

## Ubuntu 18.04
- Git
- Vim
- Use PPA, not default in ubuntu repo (they didn't compile with more features and it's earlier version of vim)
  Default also doesn't compie with clipboard feature.
- Visual studio code
- Postman
- Pgadmin
- Curl
- Discord
- Postgresql
- NPM (current known method for latest version is a command curling into bash execution (oof, yikes))
- Nodejs
- Go
- Docker

### Configuration
- Vim dotfiles

- Visual studio preferences and keybindings

- ssh

- Keyrate increase:
   
   Settings > Universal Access > Typing > Repeat keys. 
   Keep testing, no numbers provided

- Turn off notification bell

   Settings > Sound > Sound Effects > Alert volume > OFF

- Firefox

   ublock origin 

   turn off saving password request

   change cycling tab to in order and not recent tab

   about:config > mousewheel.min_line_scroll_amount = 50

- VirtualBox ssh

    settings > network > advanced > port forwarding 

    fill out name, host port (3022), guest port (22), leave rest blank, then reset machine

    ssh -p 3022 username@localhost

### Nice to know
Right ctrl + f      Full screens VM

Right ctrl + home   Open VM menu
