# practica-examen

jerarquia

- direccion
- calidad
- operativa
    -- produccion
    -- logistica
- comercial_marketing
- legal

  el criterio de jerarqui ha sido mediante secciones de la logica de negocio y un segundo criterio sobre los permisos del documento.

  posibles etiquetas
    - sede:espana,paise_Bajos,colombia,kenia
    - producto: lirios ,rosas,claveles,orquideas
    - tipo de documento: ficha_tecnica,certificadocontrato,guia
    - Temporada:verano,navidad,invierno
    - Estado:borrado,en_revision,en_proceso,archivado,rechazado,cobrado,por_cobrar
 

  10. PLANTILLA METADATOS
      ---
      codigo: FM_ES_ROS_2026_001
      titulo: ficha tecnica rosa del sesirto
      sede:españa
      version: 1.1
      reponsable: Juan Gonzalez
      fecha_creacion:01/05/2026
      fecha_revision:02/05/2026
      estado:aprobado
      palabras clave:[rosa,flor,semillas de oro,sustrato tipoC]
      ---

      11. estamos hablando de nomenclatura
          GUIAS TECNICAS DE FLORES
          FM_ESROS_2026_001.pdf
          he usado las inicial de la empresa,la sede,el codigo de producto ros=rosa año y numero de version.
          FM_cllir_2026_034.pdf



       PEDIDOS
      PDFM_01052026_097878_0534.pdf
      PED pedido´+ FM florimundi
      Sede+FECHA

      12

      issues= propuesta o incidenciaa
      - cuando  llega un documento se abre un issue para indicar el error y senvia al tecnico.
      - el tecnico crea una rama pa el documento segun tipo --> nuevas-rosas
      - edita el documento por parte del semillero
      - abre un pullrequest (peticion de aprobacion)
      - el responsable aprueba y hace un merge ,une la rama al tronco
      - le coloca la etiqueta de publicado y lo coloca en la carpeta documentos publicos
     
        estado inicial del documento,que actor tiene que hacer algo,que tiene que hacer(tarea,condiciones plazo) y cual es el estado siguiente

      13

      BORRADOR:
      ENREVISION:
      APROBADO:
      PUBLICO:
      ARCHIVADO:
      ELIMINADO


      14
                                  DIRECTOR     RESPONSAABLEAREA       EDITOR          EXTERNO

      PEDIDO                      VER          VER/EDITAR               CREAR          NADA

      GUIA TECNICA                VER          VER                     CREAR/EDITAR     VER

      CONTRATO LABORAL            EDITAR           VER                   NO             NO


      
