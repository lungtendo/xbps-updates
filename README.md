# xbps-updates
xbps-updates checker module for polybar 

[module/updates]
type = custom/script
exec = xbps-updates
format = <label>
format-prefix = 󰳡
format-prefix-foreground = #DE8C92
interval = 3600 
label = %output% 
label-padding = 1
format-foreground = #D8DEE9     

[module/reposync]
type = custom/script
exec = doas xbps-install -S 
format =
interval = 3600 
label = 
