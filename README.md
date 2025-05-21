#### changed  

   **• font**: JetBrainsMono Nerd Font  
   **• colorsheme**: Gruvbox Dark  
   **• shell**: zsh    
   **•** and some configuration  
       
#### preinstall  
        
        
    pkg update && pkg upgrade  
    pkg i git bc termux-services termux-api  
    pkg i tmux zsh fzf zoxide eza bat  

        
      
#### installation  

  ```  
  git clone https://github.com/die4kv/simple-termux.git
  cd ./simple-termux
  cp -r * ~/
  termux-reload-settings  
  ```    
     
#### after install  
    
  ```
     chsh // to zsh  
     
  ```  


#### credits  

  [ryanoasis/ners-fonts](https://github.com/ryanoasis/nerd-fonts) for the font.  
  [mayTermux/myTermux](https://github.com/mayTermux/myTermux) for colors & configs.
  [dreamsofautonomy/zenzsh](https://github.com/dreamsofautonomy/zensh) for zsh config.
