# Decisión humana — resolución de la coincidencia de relevos 3/5

```text
WORK_ID=prueba-orquestador-e2e-relevos-3-5-ai
CARRIL=K
INCOMING_TURN_ID_REANUDACION=8
PERIMETRO_ULTIMA_MODIFICACION=CONSTITUCION

WORK_CUT=https://github.com/francogg89-ai/work-claude-k@6bf2ceb0a3632c6335b1bc7dad21a7b4684094c5
AUDIT_ORIGIN_SHA=701528e2ab68c6e048bc59459d100b84ad91fcda
HUMAN_NEED_ID=H2
```

## Resolución humana literal

```text
que haga relevo del auditor y relevo del constructor, hay que decirle al constructor fresco que pida un auditor fresco
```

## Alcance interpretado de la resolución

La resolución es inequívoca para la colisión concreta detectada en la coincidencia de las primeras marcas periódicas:

```text
CONSTRUCTOR computable = 3
AUDITOR computable = 5
```

Se ejecutan ambos relevos en una sola continuidad material:

1. esta instancia AUDITOR saliente emite ahora un pase a `CONSTRUCTOR fresh`;
2. ese CONSTRUCTOR fresh reconstruye desde Git y realiza la próxima intervención material ordinaria;
3. al cerrar esa intervención, el CONSTRUCTOR no decide el relevo del AUDITOR: transporta la decisión humana y auditora ya preservada, emitiendo `next_actor="AUDITOR"` y `next_instance="fresh"`;
4. el AUDITOR fresh reconstruye desde Git y audita esa nueva entrega como su primera intervención ordinaria.

La resolución no autoriza al ORQUESTADOR a interpretar, contar ni decidir relevos.

## Alcance excluido

Esta decisión:

- resuelve únicamente esta coincidencia concreta de relevos sobre la corrida actual;
- no modifica `orchestra-revolutions-ai`, `metodo-manifiestos-ai`, `rules-orchestrator-ai` ni el manifiesto;
- no crea una regla general durable para futuras coincidencias;
- no reinicia ni desplaza ninguna grilla absoluta;
- no modifica capacidades ni fronteras estructurales de escritura;
- no vuelve `current` a ninguna instancia retirada.

## Veredicto y próxima acción

```text
VEREDICTO=H2_RESUELTA
PROXIMA_ACCION=Emitir pase ordinario a CONSTRUCTOR fresh usando el corte exacto de work 6bf2ceb0a3632c6335b1bc7dad21a7b4684094c5. El CONSTRUCTOR fresh debe reconstruir desde Git, producir la siguiente entrega material de unidad-secuencia/ conforme al PLAN y, al cerrar, emitir el pase al AUDITOR con next_instance=fresh por decisión humana ya preservada.
```

No queda una necesidad humana abierta en esta intervención.
