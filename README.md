# Diagnóstico de Hipervisor

## Paso 1 - Auditoría de Almacenamiento Local

### Comando ejecutado

```bash
sudo lvs -o lv_name,lv_size,data_percent,metadata_percent
```

### Salida obtenida

<img width="1057" height="754" alt="image" src="https://github.com/user-attachments/assets/cdf5f310-e34d-4588-8987-4e48dc5dc98d" />



---

## Paso 2 - Diagnóstico de la Red Virtual

### Comando ejecutado

```bash
brctl show
```

### Salida obtenida

<img width="1062" height="753" alt="image" src="https://github.com/user-attachments/assets/af69f53d-d19d-4862-a326-952fbc4dd7a5" />


---

## Conclusión Técnica

Se verificó que el switch virtual detectado se encuentra operativo y mantiene la interconexión entre las interfaces de red configuradas en el host. No se observaron indicios de fallas o inconsistencias en la topología de red virtual durante la auditoría realizada.

El estado actual del bridge permite una comunicación adecuada entre las máquinas virtuales y la red física, indicando una condición de funcionamiento estable para el entorno de virtualización analizado.
