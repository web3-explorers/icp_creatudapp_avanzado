# Crea tu dApp con ICP - Avanzado

Este repositorio contiene las presentaciones y códigos usados en el curso Crea tu dApp con ICP - Avanzado.

La presentación está disponible en: [Presentación](https://github.com/web3-explorers/icp_creatudapp_avanzado/blob/main/Crea%20una%20dApp%20con%20ICP%20-%20avanzado.pdf)

El curso está disponible en: https://www.youtube.com/playlist?list=PLu4f2kXcjVZb38MM-77hGVl8r4aa52TIG

## Pasos de ejecución

1. Primero, debes clonar este repositorio:
```sh
git clone https://github.com/web3-explorers/icp_creatudapp_avanzado.git
```

2. Luego, modifica los archivos de acuerdo a lo visto en el curso: https://www.youtube.com/playlist?list=PLu4f2kXcjVZb38MM-77hGVl8r4aa52TIG

3. A continuación, instala el DFinity Canister SDK (en una máquina tipo Linux):

```sh
sudo sh -ci "$(curl -fsSL https://smartcontracts.org/install.sh)"
```

4. En la misma máquina Linux, en la ruta raíz del proyecto ejecuta los siguientes pasos:

```sh
sudo npm install
sudo dfx start --background
sudo dfx deploy
```

5. En un navegador, explora la url: **http://<dominio/ip de la máquina>:8000**

## Agradecimientos

Se agradece a Paul Liu y Nick Quinlan por su repositorio de código que lo usamos de base para nuestro proyecto: https://github.com/ninegua/reversi
