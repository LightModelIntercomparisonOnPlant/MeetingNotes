# Data format for the benchmark

# What are the objects we need to represent
 - geometry of the plant in 3D
 - optical properties of each organ
 - Group of organ into groups (phytomers/axis/plant) + identifiers
 - sky + lights + dOY + lat/lon
 - soil (3D+optical)
 - optional : surronding environment (greenhouse, ...)
 - UNITS

## 3D scene

### Input Format

#### Geometry
- Geometry is **gltf** : uid for organs + mesh
- if not : *OBJ*
- or *PLY* (use blender for conversion)

* Soil?
#### Optical property
- uid : optical property (txt)

#### Lights

- sky will be represnted as various lights
- With metainformation : sky in latitude and longitude 

## Global format

- JSON 
- Metainformation
- Plants : file(s)
- Plant *topology* : group of organs at different scales : uid -> [uid]
- Environment : soil + GH
- Lights :
- Optical properties
- Results : file name 
