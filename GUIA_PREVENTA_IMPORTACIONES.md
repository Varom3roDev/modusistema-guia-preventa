# GUÍA EJECUTIVA DE CONSULTORÍA: SISTEMA DE GESTIÓN DE PREVENTAS EN TRÁNSITO E IMPORTACIONES
**Cliente Objetivo:** Gerencia General – Empresa Importadora de Alta Rotación / Carga Marítima  
**Preparado para:** Víctor  
**Enfoque Estratégico:** Maximización de Flujo de Caja, Eliminación de Stock Congelado y Control Financiero en Tiempo Real  

---

## 1. DIAGNÓSTICO ESTRATÉGICO Y EMPATÍA COMERCIAL (EL DOLOR DEL CLIENTE)

En las operaciones de importación marítima con tiempos de tránsito de **90 a 180 días (3 a 6 meses)**, el inventario flotante representa el mayor activo inmovilizado de la empresa y, al mismo tiempo, su mayor vulnerabilidad operativa si se gestiona con herramientas no especializadas (Excel, WhatsApp o ERPs rígidos tradicionales).

### Los 4 Dolores Críticos de la Gerente General:
1. **Ceguera de Inventario Flotante vs. Comprometido:**
   * La Gerente no puede responder al instante: *“¿Cuántas piezas nos quedan disponibles para vender del contenedor que atraca en 20 días?”*.
   * Riesgo constante de **sobreventa** (descontento de clientes VIP al llegar a puerto) o **subventa** (llegar con bodega llena sin haber colocado el producto).
2. **El "Cáncer" de los Apartados Fantasma (Stock Congelado):**
   * Vendedores reservan "de palabra" o con abonos simbólicos por semanas. 
   * Llega el contenedor, el comprador informal se desiste o no tiene liquidez, y la empresa pierde a compradores reales de contado durante la ventana de máxima demanda.
3. **Desorden de Cobranza Fraccionada y Asimetría Financiera:**
   * La importación exige pagos estructurados a proveedores/navieras (30% anticipo, 70% contra Bill of Lading / llegada).
   * Si la cobranza de preventa no tiene trazabilidad (anticipos del 30-50% y cobro de saldos contra aviso de fondeo/atraque), la importadora termina financiando a sus clientes sin cobrar recargo ni tener certeza de liquidación.
4. **Falta de Claridad en Rentabilidad Neta Real (Costeo CIF + Gastos Locales):**
   * No saben con precisión el margen neto por SKU hasta meses después de liquidada la aduana (demoras, almacenajes portuarios, fletes terrestres, aranceles).

---

## 2. PREGUNTAS DE PODER PARA LA REUNIÓN (CONVERSIÓN COMERCIAL)

Víctor debe liderar la conversación con preguntas que evidencien un dominio absoluto del ciclo de importación:

1. **Sobre Disponibilidad y Oportunidad:**
   > *“¿Hoy en día, cuando un cliente mayorista te pide 500 unidades de un producto que viene navegando en el Pacífico, cuánto tiempo tarda tu equipo en confirmar si están libres de verdad o si un vendedor las apartó de palabra la semana pasada?”*
2. **Sobre el Impacto Financiero de los Apartados Fantasma:**
   > *“¿Cuánto dinero calculas que se queda atrapado en mercancía que tus clientes te apartan, no liquidan al llegar al puerto y que terminas teniendo que rematar o almacenar pagando bodegaje extra?”*
3. **Sobre la Cobranza y el Flujo de Caja:**
   > *“Cuando la naviera te notifica la fecha estimada de atraque (ETA), ¿tienes un mecanismo automático que le avise a los clientes con saldo pendiente que es momento de liquidar, o tu equipo de administración pasa días llamando y mandando estados de cuenta por WhatsApp?”*
4. **Sobre la Rentabilidad Real:**
   > *“¿Tu margen comercial actual se calcula sobre el costo FOB de compra en origen, o el sistema ya te proyecta el costeo nacionalizado prorrateando flete marítimo, seguros, gastos aduanales e impuestos por metro cúbico o peso?”*

---

## 3. LOS 4 MÓDULOS CLAVE DE LA SOLUCIÓN PROPUESTA

```text
Módulo 1: Tracking de Contenedores y Stock Flotante --> Módulo 2: Catálogo Preventa y Reserva Inteligente
Módulo 2 --> Módulo 3: Conciliación de Pagos y Cartera en Tránsito
Módulo 3 --> Módulo 4: Notificaciones Automatizadas Multicanal
```

### MÓDULO 1: Radar de Importaciones y Stock Flotante
* **Ficha Técnica del Embarque:** Tracking por contenedor, naviera, B/L (Bill of Lading), fecha de zarpe (ETD), fecha estimada de llegada (ETA) y puerto de arribo.
* **Costeo Dinámico Landed Cost (Nacionalizado):**
  * Conversión automática de FOB a CIF.
  * Prorrateo de fletes, seguros y gastos portuarios/agenciamiento por volumen ($CBM$) o peso ($KG$).
  * Cálculo del costo unitario final y margen de ganancia proyectado antes de abrir la preventa.
* **Semáforo de Disponibilidad:**
  * Cantidad Embarcada | Cantidad Reservada con Anticipo | Stock Disponible para Preventa | Stock de Seguridad en Bodega.

### MÓDULO 2: Catálogo Digital de Preventa y Motor de Asignación
* **Portal de Preventa para Clientes y Fuerza de Ventas:** Visualización en tiempo real de productos que vienen en camino con fecha estimada de entrega.
* **Control de Cupos por Lote/Contenedor:** La preventa solo descuenta del contenedor asignado; si se satura, pasa en automático a lista de espera del siguiente embarque programado.
* **Regla Estricta Anti-Apartados Fantasma:** *(Ver Sección 4)*.

### MÓDULO 3: Control Financiero de Abonos, Saldos y Cartera
* **Esquema de Cobranza Escalonada (Milestone Payments):**
  * *Hito 1:* 30% a 50% de anticipo para activar la reserva.
  * *Hito 2:* Liquidación del saldo (50-70%) contra confirmación de aviso de llegada a puerto o despacho aduanero.
* **Trazabilidad de Comprobantes de Pago:** Carga de fichas de transferencia, validación administrativa y conciliación directa contra la orden de preventa.
* **Bloqueo de Despacho Logístico:** Si el saldo pendiente no está al 100% conciliado en banco, el sistema bloquea automáticamente la generación de guía de remisión o entrega de bodega.

### MÓDULO 4: Centro de Notificaciones Multicanal (WhatsApp & Email API)
* **Alertas Automatizadas al Comprador:**
  * *Al reservar:* Confirmación de apartado con liga a recibo de anticipo y desglose de saldo.
  * *Cuenta Regresiva de Reserva:* Recordatorio a las 24 y 48 horas si el anticipo no se ha subido al sistema.
  * *Aviso de Zarpe y Tracking:* "Tu pedido va navegando rumbo al puerto".
  * *Aviso de Arribo / Solicitud de Liquidación:* "El barco atraca en 5 días. Realiza tu saldo para garantizar entrega prioritaria".
* **Alertas a Gerencia:** Notificaciones de reservas canceladas automáticamente, dinero recaudado en preventa y alertas de contenedores con baja colocación comercial.

---

## 4. LA POLÍTICA RECOMENDADA "ANTI-APARTADOS FANTASMA"

Para que la Gerente General elimine la fricción y las pérdidas por inventario apartado sin compromiso real, el software implementa un **Motor de Caducidad de Reservas (Auto-Release Inventory)**:

1. **Ventana de Reserva Temporal (Pre-reserva):**
   * Cuando un cliente o vendedor genera una orden de preventa, el inventario se aparta por un lapso improrrogable de **48 a 72 horas hábiles**.
2. **Requisito de Anticipo Obligatorio:**
   * Para consolidar la reserva, debe registrarse el pago de mínimo el **30% o 50% del valor total** (según política por categoría de producto).
3. **Liberación Automática (Auto-Drop):**
   * Si tras 72 horas no se adjunta ni valida el comprobante del anticipo, el sistema libera el stock al inventario general disponible a las 00:00 hrs.
   * Se envía un WhatsApp cordial al cliente: *“Tu solicitud de reserva ha vencido. El producto ha vuelto a estar disponible para el público general.”*
4. **Beneficio Financiero Inmediato:**
   * Cero stock congelado por clientes indecisos.
   * La fuerza de ventas compite por clientes con liquidez real.
   * El 100% de la preventa registrada cuenta con respaldo de flujo en cuenta bancaria.

---

## 5. DASHBOARDS GERENCIALES: CONTROL TOTAL EN UN PANTALLAZO

Víctor debe mostrar a la Gerente cómo lucirá su día a día gerencial:
* **KPI 1: Nivel de Colocación en Tránsito (% Pre-sold):** Meta del 60% al 85% vendido antes de tocar puerto.
* **KPI 2: Liquidez Recaudada en Preventa ($):** Flujo de caja disponible para pagar impuestos aduanales y fletes locales sin requerir deuda bancaria.
* **KPI 3: Tasa de Conversión de Reservas vs. Abandonos:** Medición del impacto del motor anti-apartados.
* **KPI 4: Margen Bruto y Neto en Vivo:** Utilidad proyectada considerando variaciones en tarifas de flete y tipo de cambio.

---

## 6. GUION DE CIERRE Y SIGUIENTES PASOS PARA VÍCTOR

* **Propuesta de Fase 1 (Quick Win):**  
  > *“Podemos implementar la plataforma centralizando tus próximos contenedores en tránsito en menos de 3 a 4 semanas. Tendrás el catálogo en vivo, la regla de auto-liberación a 72 horas y el control de anticipos operando antes del próximo zarpe.”*
* **Llamado a la Acción:**  
  > *“Agendemos una sesión técnica de 45 minutos para revisar tu formato actual de B/L y packing list, y configurar el modelo de costeo Landed en un prototipo funcional con sus propios números.”*

---

## 7. ANEXO TÉCNICO: VALIDACIÓN DE FACTIBILIDAD Y ARQUITECTURA DE SOFTWARE (PRESENTACIÓN A GERENCIA)

El equipo de ingeniería de software ha auditado la viabilidad técnica de los tres requerimientos estratégicos planteados para la plataforma de preventas de Modusistema:

### 1. Automatización del Inventario Flotante en Tránsito
* **Factibilidad:** **100% Viable** mediante arquitectura relacional con integridad transaccional (ACID).
* **Mecanismo Operativo:**
  * Modelado de entidades vinculadas al Bill of Lading (B/L), naviera, hitos logísticos (ETD, ETA proyectada, fondeo, atraque, nacionalización) y desglose de SKUs embarcados.
  * **Cero riesgo de sobreventa o descuadre:** El inventario disponible se calcula reactivamente en base de datos:
    $$\text{Stock Disponible Preventa} = \text{Stock Embarcado} - \text{Reservas Confirmadas} - \text{Pre-reservas Activas}$$
  * Generación de semáforos por contenedor en tiempo real para fuerza de ventas y gerencia general.

### 2. Gestión de Apartados con Liberación Automática en 72 Horas
* **Factibilidad:** **100% Viable** mediante tareas programadas (Background Workers / Scheduled Cron Jobs) y webhooks transaccionales.
* **Mecanismo Operativo:**
  * Al generarse una pre-reserva, el sistema fija la marca de caducidad: `expira_en = fecha_creacion + 72 horas`.
  * Un proceso en segundo plano verifica periódicamente las órdenes: si se alcanzan las 72 horas sin confirmación administrativa del anticipo (30-50%), la reserva expira automáticamente, las unidades vuelven de inmediato al inventario disponible para el resto del equipo comercial y se emite una notificación cordial multicanal (WhatsApp/Email API).

### 3. Motor de Costeo Landed Dinámico (Nacionalizado)
* **Factibilidad:** **100% Viable** mediante motor paramétrico multivariable.
* **Mecanismo Operativo:**
  * Prorrateo automático de fletes y seguros marítimos por **volumen ($CBM$)** o **peso bruto ($KG$)** de cada SKU dentro del contenedor.
  * Prorrateo de aranceles, agenciamiento aduanal e impuestos portuarios por valor CIF.
  * **Estrategia en 2 fases:**
    1. *Costo Landed Proyectado (Preventa):* Fija precios de venta y protege el margen comercial con estimaciones logísticas antes del zarpe.
    2. *Costo Landed Liquidado (Real):* Ajusta al centavo la rentabilidad neta final una vez liquidada la factura aduanal definitiva.