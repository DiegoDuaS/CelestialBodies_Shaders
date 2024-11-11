# CelestialBodies_Shaders

Este proyecto se basa en realizar differentes Shaders para 7 cuerpos celestes diferentes. Muchos de los Shaders de este proyecto utilizaron mapas de ruido para diferentes resultados. A continuacion se pueden ver imagenes de cada uno de los cuerpos.

## Cuerpos Celestes

### Sol
![image](https://github.com/user-attachments/assets/6d569d0e-1773-483e-bee6-1970381f0e64)

### Volcanis
![image](https://github.com/user-attachments/assets/cab70bd9-7c82-4c7c-a574-928504807f7b)

### Morveth
![image](https://github.com/user-attachments/assets/5a48a534-8c88-44f6-b8eb-5def2a36ac86)

### Gaia Nova
![image](https://github.com/user-attachments/assets/1c08685e-eb2d-4301-a0b8-1262afe69efc)

### Aquarion
![image](https://github.com/user-attachments/assets/82f9e07c-05b8-407a-bb2b-89a5af983f16)

### Stratos
![image](https://github.com/user-attachments/assets/cb99323f-db96-4b48-8f98-5afcc27b504f)

### Kraton V
![image](https://github.com/user-attachments/assets/69796e9c-e7c1-4462-97fa-8dddb9845199)

## Correr el Proyecto 

1. Clona el repositorio en tu máquina
```bash
git clone https://github.com/DiegoDuaS/CelestialBodies_Shaders.git
cd CelestialBodies_Shaders
```

2. Compila el código
```bash
cargo build --release
```

3. Corre la versión optimizada
```bash
 ./target/release/CelestialBodies_Shaders
```

Para modificar que se puede observar, debes de hacer cambios en las siguientes lineas 

### main.rs
- 32: Descomenta los ruidos necesarios
- 245: Cambia el nombre del archivo

## shaders.rs
- 48: Escribe el shader que quieras utilizar 

Para los cuerpos mostrados, estos son sus propiedades:
### Sol
Archivo: cuerpo2.obj
Ruido: create_sun_noice
Shader: sun_shader

### Volcanis
Archivo: cuerpo2.obj
Ruido: create_plant3_noice
Shader: lava_planet_shader

### Morveth
Archivo: cuerpo2.obj
Ruido: create_plant1_noice
Shader: planet1_shader

### Gaia Nova
Archivo: cuerpo2.obj
Ruido: create_cloud_noice
Shader: earth_map_shader

### Aquarion
Archivo: cuerpo2.obj
Ruido: create_water_noice
Shader: water_shader

### Stratos
Archivo: saturno2.obj
Ruido: create_plant2_noice
Shader: gas_giant_shader

### Kraton V
Archivo: asteroide.obj
Ruido: create_rock_noice
Shader:  rock_shader
