# Infraestructura IT segura para una startup de TCG

## Descripción
Trabajo de Fin de Grado correspondiente al ciclo formativo de Grado Superior de Administración de Sistemas Informáticos en Red (ASIR).

El proyecto consiste en el diseño e implementación desde cero de una infraestructura IT segura para una startup del sector Trading Card Games (TCG), combinando una tienda física con su correspondiente arquitectura de red segmentada.

## Autor
Miguel Ángel Aranda Martínez

## Tutor
Numién Joost-Newbery Palavecino

## Centro
UAX FP — Universidad Alfonso X el Sabio

## Tecnologías utilizadas
- Cisco Packet Tracer (simulación de red)
- Draw.IO (diagramas de topología)
- Microsoft Word (documentación)
- OBS Studio (grabación del vídeo demostrativo)
- Adobe Premiere Pro (edición del vídeo)
- DeepL (traducción del Abstract)

## Contenido del repositorio
- `TFG_Miguel_Angel_Aranda.pdf` — Documento completo del TFG
- `red_tienda_tcg.pkt` — Simulación de red en Cisco Packet Tracer

## Arquitectura de red implementada
- Router Cisco 2811
- Switch Cisco 2960-24TT
- VLAN 10 — Red Clientes (192.168.10.0/24)
- VLAN 20 — Red Interna (192.168.20.0/24)
- ACLs extendidas para control de acceso entre VLANs
- DHCP configurado en el router para ambas VLANs

## Curso
2025-2026
