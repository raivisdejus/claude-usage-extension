# Claude usage extension
![GNOME Shell 48+](https://img.shields.io/badge/GNOME%20Shell-48%2B-blue)   

A GNOME Shell extension that displays your Claude Code API usage percentage in the top panel. 

## Features                                                                                                                                                                                                      
                                                                                                                                                                                                                   
- **Real-time usage monitoring** - View your 5-hour and 7-day Claude Code usage                                                                                                                                  
- **Settings menu*** - Change the layout or the refresh time                                                                                                                                              
                                                                                                                                                                                                            
## Requirements                                                                                                                                                                                                  
                                                                                                                                                                                                                   
- GNOME Shell 48 or later                                                                                                                                                                                        
- Claude Code installed and authenticated (`~/.claude/.credentials.json`)   

## Installation                                                                                                                                                                                                  

```bash
git clone https://github.com/Haletran/claude-usage-extension
cp -r claude-code-usage ~/.local/share/gnome-shell/extensions/claude-usage@haletran.com 
cd ~/.local/share/gnome-shell/extensions/claude-usage@haletran.com/schemas                                                                                                                                      
glib-compile-schemas .
## Restart Gnome Shell with Alt + F2 type r or logout
## Then enable the extension
```
