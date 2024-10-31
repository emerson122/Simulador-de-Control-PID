## ¿Qué es un controlador PID?
Un controlador PID (Proporcional, Integral, Derivativo) es un mecanismo de control por realimentación ampliamente usado en sistemas de control industrial. Este simulador te permite experimentar con los tres componentes principales:

### Componentes:
Proporcional (Kp): Produce una salida proporcional al error actual. Un valor más alto significa una respuesta más agresiva.

### Integral (Ki): Suma el error a lo largo del tiempo. Ayuda a eliminar el error en estado estacionario.
### Derivativo (Kd): Responde a la tasa de cambio del error. Ayuda a reducir el sobreimpulso y mejorar la estabilidad.
## Métricas de Rendimiento:
### Tiempo de Estabilización: Tiempo que tarda el sistema en alcanzar y mantener un valor cercano al objetivo.
### Sobreoscilación: Porcentaje que la respuesta sobrepasa el valor objetivo.
### Error en Estado Estable: Diferencia entre el valor final y el objetivo.
### Consejos de Ajuste:
- Comienza con solo el control proporcional (Ki = Kd = 0)
- Aumenta Ki gradualmente para eliminar el error en estado estable
- Añade Kd para reducir la sobreoscilación si es necesario