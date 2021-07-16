# PocketSat MVP-1

Guidelines:
      Usar Componentes Comerciales (COOT - Commecirally of the shelf). 
      Deseable verificar Space Heritage de c/componente.
      Evolucion tecnologica iterativa paso a paso.
      No desarrollar estaciones terrenas, utilizar estaciones terrenas ya disponibles.



Subsistemas:


CPU - OBC (On board Computer)
      CPUs:
          - ATMEGA328P
          - STM32F407IGT (con Heritage Espacial - ARM Cortex-M4) [Universitwin]
      Memorias FRAM (Mejor retencion de datos en el espacio): FM24V10-G (con Heritage Espacial)
      Watchdog (Para controlar que no haya frezze)
      FreeTROS es el sistema operativo más utilizado
      Cubesats PCBs: PC/104 standard: 94mm x 94mm

IMU:
      MPUXXXXX

Posicionamiento:
      GPS / GNSS
      Algoritmo 


Potencia:
      Paneles Solares
      Baterias

Radio:
      UHF (433Mhz)
      Lora (Long Rage distance)
      S Band (2,4Ghz)
      X Band
      Antenna (Dipole - Measure Tape)

Estructura:
      Se disena en CAD
      Fijaciones Tornillos
      Se verifican con Software de analisis de elementos finitos

Estaciones Terrenas:
      Usar estaciones terrenas ya disponibles
      Amazon Ground Station (https://aws.amazon.com/es/ground-station/)
      Satgnos (https://satnogs.org/)
      TinyGS (LoraWAN) (https://tinygs.com/)


Lanzadores / Lanzamientos:
      Si se lanza desde USA, se puede tener que cumplir con normas ITAR.
      




Proyectos Referencia:
      Universitwin. 1U dentro de satelite de Satelogic.
      Bartolomeo (Airbus): Modulo dentro de la IIS para poner cargas utiles. Desde 3U hasta 450kg. Airbus se encarga de todo el ciclo de vida. 300k a 400k EUR por 3U al año. <12 meses.
      
      

Documentacion:
      NASA Systems Engineering Handbook
      

