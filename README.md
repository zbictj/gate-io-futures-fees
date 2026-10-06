# comisiones futuros gate io: qué pagas en maker, taker y funding, y cómo bajar la factura sin operar de más

Si has llegado buscando "comisiones futuros gate io", probablemente quieras dos cosas: el número exacto y saber si ese número se queda ahí.

El número corto: en el nivel base, un perpetuo con margen en USDT cuesta **0,020% si pones la orden en el libro (maker)** y **0,050% si la cruzas (taker)**. El resto de la respuesta es más interesante, porque ese 0,05% es solo una parte de lo que pagas. En según qué estilo de trading, es la parte pequeña.

## Cómo se calcula la comisión de un futuro en Gate

Gate cobra al abrir, al cerrar y al reducir posición. Una orden límite que no se ejecuta, o que cancelas, no genera comisión. Hasta aquí, como casi todos.

Lo que se malinterpreta es la base de cálculo:

`comisión = valor de la posición × tasa maker o taker`

El valor de la posición es el nocional, no el margen que depositas. Con 1.000 USDT de margen y 10x abres una posición de unos 10.000 USDT. Con taker al 0,05%, esa apertura cuesta 5 USDT; cerrarla en condiciones parecidas, otros 5. Redondo: unos 10 USDT por ida y vuelta.

El apalancamiento no encarece la comisión de una misma posición. 10.000 USDT de nocional pagan lo mismo a 5x que a 50x. Lo que hace el apalancamiento es acercar la liquidación, y eso ya no es una comisión, es dinero que desaparece si el precio se mueve en tu contra.

Dos aclaraciones que ahorran discusiones:

- **Maker** es la orden que entra al libro y espera. Aporta liquidez, por eso se paga menos. Las tasas maker no admiten descuento con tarjetas de puntos.
- **Taker** es la orden que se ejecuta contra algo que ya estaba. Una orden límite puede terminar siendo taker si se cruza al instante; no decide el botón, decide el modo de ejecución.

Las comisiones de futuros se descuentan del margen de la posición, no de tu saldo spot.

## Las comisiones base por tipo de contrato

No todos los futuros de Gate comparten cuadro de tarifas. Este es el punto de partida en el nivel VIP 0:

| Producto | Maker | Taker | Cuándo se paga |
| --- | --- | --- | --- |
| Perpetuos con margen en USDT (BTC, ETH, altcoins) | 0,0200% | 0,0500% | Al abrir, cerrar o reducir |
| Perpetuos TradFi con margen en USDT (acciones, metales, índices, forex, materias primas) | 0,0200% | 0,0500% | Cuadro propio desde el 1 de septiembre de 2026 |
| Futuros de entrega con margen en USDT | -0,015% (rebaja) | 0,016% | Al operar; tasa de entrega del 0,015% |
| Opciones | Esquema separado | Esquema separado | Revisar la página de tarifas |
| Alpha (tokens on-chain) | 0,8% fijo | 0,8% fijo | Igual en todos los niveles VIP |
| Spot, como referencia | 0,10% | 0,10% | 0,09% si pagas con GT |

Ese maker negativo de los contratos de entrega no es un error de escritura: son contratos con fecha de vencimiento y sin liquidación de funding, y Gate paga por aportar liquidez. No es lo que usa el 90% de la gente que opera perpetuos, pero existe y a veces se pasa por alto.

👉 [Abrir cuenta en Gate y ver las tarifas aplicadas a tu perfil](https://bit.ly/GateVIP)

## Los escalones VIP en futuros, uno por uno

A partir de aquí empieza lo útil. Gate reparte las comisiones de futuros en 17 niveles, de VIP 0 a VIP 16. Así queda la escalera de perpetuos:

| Nivel VIP | Maker | Taker | Acceso |
| --- | --- | --- | --- |
| VIP 0 | 0,0200% | 0,0500% | [Registrarte para empezar en VIP 0](https://bit.ly/GateVIP) |
| VIP 1 | 0,0200% | 0,0500% | [Comprobar requisitos y crear cuenta](https://bit.ly/GateVIP) |
| VIP 2 | 0,0200% | 0,0500% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 3 | 0,0200% | 0,0480% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 4 | 0,0200% | 0,0480% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 5 | 0,0200% | 0,0450% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 6 | 0,0180% | 0,0420% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 7 | 0,0160% | 0,0375% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 8 | 0,0140% | 0,0350% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 9 | 0,0120% | 0,0320% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 10 | 0,0100% | 0,0300% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 11 | 0,0080% | 0,0280% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 12 | 0,0060% | 0,0260% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 13 | 0,0050% | 0,0240% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 14 | 0,0020% | 0,0220% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 15 | 0% | 0,0180% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |
| VIP 16 | 0% | 0,0160% | [Ver condiciones de nivel](https://bit.ly/GateVIP) |

Tres lecturas rápidas de esa tabla:

El maker no baja nada hasta VIP 6. Entre VIP 0 y VIP 5 tu orden puede descansar en el libro toda la tarde y pagarás exactamente lo mismo que si hubieras cruzado el spread. Si tu estrategia se basa en órdenes límite, los primeros cinco niveles no te dan nada por ese lado; solo te rebajan el taker.

El maker cero llega en VIP 15. Quince escalones para llegar a un número que otras plataformas publican como tarifa estándar.

Y la bajada grande de taker, del 0,0300% al 0,0160%, se concentra a partir de VIP 10. Ahí ya no hablamos de un trader de fin de semana.

### Cómo se sube de nivel (y la trampa del volumen en futuros)

Tu nivel se asigna por el mejor de dos caminos: volumen ponderado de los últimos 30 días o promedio de tenencia de GT de los últimos 14 días. Se recalcula cada mes, y el volumen no cuenta igual según el producto:

- Spot (incluido Convert) y acciones: 100%
- Perpetuos en USDT, perpetuos en BTC y futuros de entrega en USDT: 40%
- Perpetuos en USD1 y opciones: 20%
- CFD: 10%

Ahí está el detalle que fastidia a más gente de la que debería. Si solo operas perpetuos, cada dólar de volumen cuenta un 40%. Para alcanzar el mismo nivel que un trader de spot, necesitas 2,5 veces más nocional. Los umbrales orientativos son 60.000 USD para VIP 1, 1.000.000 para VIP 5 y 50.000.000 para VIP 9, siempre medidos con esa ponderación.

Si tu idea es escalar por tenencia en lugar de por volumen, Gate también lo contempla: la vía alternativa es el promedio diario de GT (incluido GT2) de los últimos 14 días. El detalle exacto de cuánto GT pide cada nivel cambia con el tiempo y con el precio del token, así que conviene mirarlo en la página de tarifas antes de comprar GT pensando en una rebaja que quizá no llegue.

## El cargo que no aparece en la tabla: funding

Cuando alguien pregunta por las comisiones de futuros en Gate, casi siempre se refiere al maker y al taker. El funding es otra cosa y se lleva dinero igual.

Es el pago periódico entre largos y cortos para que el precio del perpetuo no se despegue del spot. Gate no se queda ese dinero: lo transfiere de una parte a la otra. Dos consecuencias prácticas:

- Si el funding es positivo, pagan los largos. Si es negativo, pagan los cortos. Puede ser un coste o un ingreso.
- Se calcula sobre el valor nocional: `funding = valor de la posición × tasa de funding`.

Los perpetuos de cripto liquidan cada 8 horas a las 00:00, 08:00 y 16:00 UTC. Algunos contratos usan ciclos de 4 horas o incluso de 1 hora, y el ciclo aparece en la ficha del contrato. La tasa base para contratos cripto es del 0,03% diario; para contratos TradFi es del 0%.

Un ejemplo con números redondos: 20.000 USDT de posición larga, dos liquidaciones de funding a +0,01% cada una, son 4 USDT. Al lado de los 20 USDT de comisiones de apertura y cierre al 0,05% taker, parece poco. Si la tasa se va a +0,1% por sesión en una altcoin en plena tendencia alcista, el funding se come la comisión y el almuerzo.

De ahí una regla simple: si abres y cierras el mismo día, mira el maker y el taker. Si vas a mantener posiciones días o semanas, mira el funding primero.

## Otras familias de contratos con reglas propias

Gate ha ido separando cuadros de tarifas que antes iban juntos, y eso confunde a quien mira guías antiguas.

Desde el 1 de septiembre de 2026, los perpetuos TradFi con margen en USDT (acciones, metales, índices, forex y materias primas) usan un cuadro independiente del resto de perpetuos. Los requisitos de volumen y los criterios para subir de nivel no cambiaron: solo cambió la tasa aplicada a esa familia.

En esa misma línea hay una campaña de descuento en la comisión taker para perpetuos con margen en USDT. Quien entra en el programa recibe un descuento del 9%, 16% o 20% según su peso en el volumen taker total de la plataforma, medido en tramos (X entre 0,02% y 0,2% para el primer nivel; 0,2% a 1% para el segundo; 1% o más para el tercero). Se solicita a través del gestor de cuentas, no se activa solo. Si el mes siguiente no alcanzas el primer tramo, vuelves a la tarifa estándar.

Para los market makers hay otro carril: los niveles MM de los perpetuos TradFi van de 0% (MM 0) a rebajas de -0,003%, -0,004% y -0,005% según el nivel asignado, es decir, cobrar por operar en lugar de pagar. Ese mundo existe, pero exige cumplir condiciones de cotización que no están al alcance de una cuenta minorista normal.

Y una advertencia sobre las promociones: existen campañas rotativas con maker 0% o comisiones cero en pares concretos, y son reales. Lo que no son es permanentes ni universales. Si cuentas con ellas en tu cálculo de rentabilidad a tres meses, revisa su estado antes de operar.

## Cómo reducir la factura sin operar más

Este es el apartado donde más se equivoca la gente. Operar más para bajar de nivel tiene un problema obvio: para ganar 0,005 puntos porcentuales de comisión puedes perder bastante más en el mercado y en el funding. El volumen como estrategia de ahorro solo tiene sentido si ya lo vas a generar de todas formas.

Lo que sí funciona y no requiere volumen extra:

**Vales de reembolso.** Gate emite vales que devuelven una parte de las comisiones de spot y futuros. Se activan manualmente, solo uno a la vez, y el reembolso se abona antes de las 23:59:59 (UTC+0) del día siguiente. Cuando el vale caduca, el saldo que quede no sirve. Una fuente de dinero que mucha gente tiene sin activar.

**Pago de comisiones con GT.** Aplica a las comisiones de spot: en VIP 0, la tarifa pasa de 0,10% a 0,09%. Ojo con el automatismo: si activas la deducción y se te acaba el GT, el sistema cobra la tarifa VIP estándar sin avisar. Si hiciste presupuesto con 0,09%, la sesión puede terminar al 0,10%.

**Concentrar volumen en campañas.** Si ya vas a hacer un pico de operaciones, hazlo coincidir con un evento sin comisiones. El volumen cuenta igual para subir de nivel y, de paso, no pagas.

**Superar el nivel de cuenta adecuado.** Las cuentas de subcuenta custodiadas no entran en el programa de descuento de taker. Si operas desde una, no esperes el descuento.

**Usar órdenes límite cuando la estrategia lo permita.** No es un truco de plataforma, es aritmética: 0,020% contra 0,050% es una diferencia de 2,5 veces en cada operación completada.

👉 [Comprobar los vales y bonos disponibles al crear la cuenta](https://bit.ly/GateVIP)

## Cuánto pesa todo junto: dos estilos de trading

Vamos con un ejemplo para darle textura. Cuenta nueva, VIP 0, posición de 20.000 USDT en un perpetuo con margen en USDT, ida y vuelta completa.

**Estilo taker:** apertura 0,050% (10 USDT) más cierre 0,050% (10 USDT) son 20 USDT. Dos liquidaciones de funding a +0,01% suman 4 USDT. Total aproximado: 24 USDT. Y ojo con el slippage: no es una comisión de Gate, pero si la ejecución te cuesta un 0,03% en cada extremo, añade otros 12 USDT que no aparecen en ninguna tabla.

**Estilo maker:** si consigues que ambas órdenes se ejecuten como maker, la parte de comisión baja a 0,020% casi por lado, unos 8 USDT. El funding, en cambio, lo pagas igual.

Doce USDT de diferencia en una sola operación no parece gran cosa. Multiplícalo por 20 operaciones al mes y son 240 USDT al año sin cambiar de estrategia, solo de tipo de orden. Ese es el verdadero argumento para mirar el cuadro de comisiones antes de elegir el par, no la comparación abstracta entre exchanges.

## Dónde ver tus tarifas reales

La tabla de arriba es el esquema publicado, pero tu cuenta tiene su propia tarifa aplicada, y esa es la que se descuenta. La forma limpia de comprobarla:

1. Crea la cuenta y completa la verificación de identidad. Sin KYC no hay futuros ni retiradas en condiciones normales.
2. Entra en la página de tarifas de Gate y mira la pestaña de futuros con tu sesión iniciada: los valores cambian respecto a la vista sin login.
3. Opera una posición pequeña y revisa el detalle de la operación. Ahí ves la tasa exacta que te aplicaron, el importe en USDT y el producto.
4. Si operas perpetuos TradFi, confirma la tasa en la ficha del contrato: ese cuadro va por separado.

Y un aviso práctico que conviene saber antes de mover dinero: los residentes en Estados Unidos se encuentran con restricciones en el sitio global de Gate. Comprueba tu país antes de registrarte.

## Preguntas frecuentes

**¿Gate cobra comisión si dejo una orden sin ejecutar?** No. Solo se paga cuando hay ejecución, sea apertura, reducción o cierre. Cancelar no cuesta nada.

**¿El apalancamiento alto encarece las comisiones?** No para un mismo valor de posición. La comisión depende del nocional. Lo que sube con el apalancamiento es el riesgo de liquidación y, si hay poco margen, la velocidad a la que el funding te erosiona la cuenta.

**¿Quién cobra el funding?** Nadie de la plataforma. Se paga de una pata a la otra. Gate solo ejecuta la transferencia al precio y la tasa que correspondan.

**¿Es más barato que otros exchanges?** El maker base de 0,020% es competitivo; el taker de 0,050% está en línea con los grandes, ni el más barato ni el más caro. La diferencia real aparece en los niveles altos y en las promociones puntuales, no en la tarifa base.

**¿Hay bono por registrarse?** La página de registro suele mostrar bonos de bienvenida y fondos de prueba, pero el importe y las condiciones cambian por región y campaña. Míralo en la propia pantalla de registro antes de darlo por hecho.

## Para cerrar

La respuesta a "comisiones futuros gate io" cabe en una línea: 0,020% maker y 0,050% taker en el nivel base, calculado sobre el valor de la posición. Lo que decide tu factura real es otra cosa. Tres cosas, en concreto: si operas con límite o a mercado, cuánto tiempo mantienes la posición, y cuánto volumen generas para subir de nivel con una ponderación del 40% en futuros.

Con esas tres variables en la cabeza, el cuadro de tarifas deja de ser un documento aburrido y pasa a ser lo que es: la parte de tu estrategia que puedes controlar sin acertar ninguna dirección de precio.

👉 [Crear la cuenta en Gate y empezar desde VIP 0](https://bit.ly/GateVIP)
