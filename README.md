# Controlling_Sonoff_With_Alexa_And_Home_Assistant
Controlling Sonoff with alexa and Home Assistant


Add Follwoing in config file.

mqtt:

light:
  
  '-' platform: 'mqtt'
  
    name: 'Office light1'
    
    state_topic: 'office/light/status'
    
    command_topic: "office/rgb1/light/switch"
    
    optimistic: false
