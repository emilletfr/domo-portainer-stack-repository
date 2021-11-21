# domo-portainer-stack-repository
domo portainer stack repository


/home/pi/Documents/zigbee2mqtt-data/configuration.yaml 

homeassistant: false
permit_join: true
mqtt:
  base_topic: zigbee2mqtt
  server: mqtt://mqtt
serial:
  port: /dev/ttyUSB0
frontend:
  port: 8080
devices:
  '0x00158d0003f4bdbd':
    friendly_name: LivingRoom-Climate
  '0x14b457fffe669be6':
    friendly_name: DiningRoom-Light
  '0x00158d00041138e0':
    friendly_name: Corridor-Middle-Light
  '0x00158d0004113709':
    friendly_name: Corridor-Front-Light
  '0x086bd7fffe5c7a8f':
    friendly_name: Bathroom-Left-Light
  '0x086bd7fffe4d4499':
    friendly_name: Bathroom-Right-Light
  '0x00158d0003984bc9':
    friendly_name: LivingRoom-Plug
  '0x00158d000462c772':
    friendly_name: LivingRoom-Occupancy
  '0x00158d000411b87e':
    friendly_name: Corridor-Occupancy
  '0x00158d0004485c95':
    friendly_name: Bathroom-Occupancy
  '0x00158d0004519495':
    friendly_name: WC-Occupancy
  '0xec1bbdfffeaa8cc4':
    friendly_name: WC-Light
  '0x14b457fffe75e798':
    friendly_name: Kitchen-Light
  '0x00158d0004473e55':
    friendly_name: Kitchen-Occupancy
  '0x00158d000451249c':
    friendly_name: Office-Occupancy
  '0xec1bbdfffe90f58e':
    friendly_name: Office-Light
  '0x000b3cfffef04cdf':
    friendly_name: Office-Plug
  '0x00158d0003f13528':
    friendly_name: Outdoor-Climate
  '0x00158d0002b9309e':
    friendly_name: Garage-Door-Vibration
  '0x00158d00044944e4':
    friendly_name: DiningRoom-Occupancy

