# pycaret  (https://youtu.be/2PasMDMGK-I)

Despues de instalada la distribucion Anaconda

- conda env list : Me permite ver entornos virtuales creados en anaconda
- conda create --name pycaret3_light python=3.8 (Esta es la version light de pycaret)
- conda activate pycaret3_light

Dentro del entorno pycaret3_light instalo pycaret

-pip install --pre pycaret

Y luego creamos a notebook kernel

Revisamos los kernel que tengo creados:
- pip install jupyter
- jupyter kernelspec list

Creamos notebook kernel
- python -m ipykernel install --user --name pycaret3_light --display-name "pycaret3_light"

- Ahora, si entro a jupyter lab debo ver los kernel que tengo

- jupyter lab  

- ![image](https://github.com/cprieto76/pycaret/assets/115907710/9bc8ed5a-1798-436f-8dc5-d90daf400306)

Puedo ahora dar click en el kernel respectivo (pycaret3_light) y revisar la version de pycaret que deje instalado con el comando:
- from pycaret.utils import version
- version()

![image](https://github.com/cprieto76/pycaret/assets/115907710/c858e552-28d2-463f-814c-92d86c403d7c)



- 
