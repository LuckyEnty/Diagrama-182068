block-beta
  columns 8

  %% Define global styles for better readability
  classDef hidden fill:none,stroke:none,color:transparent,width:0px,height:0px;
  classDef crmSRM_node fill:#68BD45,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef crmSRM_edge stroke:#68BD45,stroke-width:3px;
  classDef sales_node fill:#FF9900,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef sales_edge stroke:#FF9900,stroke-width:3px;
  classDef purch_node fill:#1E90FF,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef purch_edge stroke:#1E90FF,stroke-width:3px;
  classDef prod_node fill:#800080,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef prod_edge stroke:#800080,stroke-width:3px;
  classDef serv_node fill:#FFFF00,stroke:#000,color:#000,rx:15,ry:15,width:130px;
  classDef serv_edge stroke:#FFFF00,stroke-width:3px;
  classDef inv_node fill:#808080,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef inv_edge stroke:#808080,stroke-width:3px;
  classDef fin_node fill:#FF0000,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef fin_edge stroke:#FF0000,stroke-width:3px;
  classDef rep_node fill:#EE82EE,stroke:#000,color:#fff,rx:15,ry:15,width:130px;
  classDef rep_edge stroke:#EE82EE,stroke-width:3px;
  classDef dashed_edge stroke-dasharray: 5 5;

  %% Header Row: Functional Areas
  headerCRM("CRM / SRM") class:crmSRM_node
  headerSales("Ventas") class:sales_node
  headerPurch("Compras") class:purch_node
  headerProd("Producción") class:prod_node
  headerServ("Servicio") class:serv_node
  headerInv("Inventario") class:inv_node
  headerFin("Finanzas") class:fin_node
  headerRep("Reportes") class:rep_node

  %% Row 1: Top-level Inputs & Definitions
  space11::::hidden space12::::hidden space13::::hidden
  BOM("Lista de Materiales") class:prod_node
  CEC("Tarjeta de Equipo de Cliente") class:serv_node
  ITM("Maestro de Artículos") class:inv_node
  CA("Plan de Cuentas") class:fin_node
  space18::::hidden

  %% Inter-row Connections 1-2
  BOM -- "Datos" --> MRP class:prod_edge
  CEC -- "Equipos" --> SC class:serv_edge
  ITM -- "Artículos" --> WM class:inv_edge
  CA -- "Cuentas" --> GL class:fin_edge
  CEC -- "Producto de Servicio" --> SO class:serv_edge,dashed_edge
  ITM -- "Gestión de Artículos" --> SQu class:inv_edge,dashed_edge

  %% Row 2: Basic Operations & Planning
  ACT("Actividades") class:crmSRM_node
  space22::::hidden
  PRq("Solicitud de Compra") class:purch_node
  MRP("Planificación de Requerimientos de Material") class:prod_node
  SC("Llamada de Servicio") class:serv_node
  WM("Gestión de Almacenes") class:inv_node
  GL("Cuentas de Mayor General") class:fin_node
  space28::::hidden

  %% Inter-row Connections 2-3
  ACT -- "Interacciones" --> CUS class:crmSRM_edge
  PRq -- "Aprov." --> PQu class:purch_edge
  MRP -- "Órdenes" --> SOU class:prod_edge
  SC -- "Contrato" --> SCo class:serv_edge
  WM -- "Niveles" --> SO class:inv_edge,dashed_edge
  GL -- "Afectación" --> GLAD class:fin_edge

  %% Row 3: Main Customer & Supplier Data / Core Documents
  CUS("Cliente") class:crmSRM_node
  space32::::hidden
  space33::::hidden
  SOU("Sourcing") class:prod_edge
  SCo("Contrato de Servicio") class:serv_node
  space36::::hidden
  GLAD("Determinación de Cuentas G/L") class:fin_node
  space38::::hidden

  %% Inter-row Connections 3-4
  CUS -- "Cotiz." --> OPP class:crmSRM_edge
  SOU -- "Cotiz." --> PQu class:prod_edge,dashed_edge
  SCo -- "Factur." --> SB class:serv_edge
  GLAD -- "Registros" --> CAc class:fin_edge
  CUS -- "Asociado" --> BPM class:crmSRM_edge,dashed_edge
  SCo -- "Soporte" --> DN class:serv_edge,dashed_edge

  %% Row 4: Opportunity & Bidding / Middle Documents
  OPP("Oportunidad") class:crmSRM_node
  SQu("Cotización de Ventas") class:sales_node
  PQu("Cotización de Compra") class:purch_node
  space44::::hidden
  SB("Facturación de Servicio") class:serv_node
  space46::::hidden
  CAc("Contabilidad de Costos") class:fin_node
  space48::::hidden

  %% Inter-row Connections 4-5
  OPP -- "Aprov." --> SQu class:crmSRM_edge,dashed_edge
  SQu -- "Precio" --> PRI class:sales_edge
  PQu -- "Orden" --> PO class:purch_edge
  PRI -- "Orden" --> SO class:sales_edge
  SB -- "Facturación" --> FP class:serv_edge,dashed_edge
  CAc -- "Asiento" --> JE class:fin_edge

  %% Row 5: Pricing & Orders / Main Transactional Documents
  PRI("Fijación de Precios") class:sales_node
  SO("Orden de Venta") class:sales_node
  PO("Orden de Compra") class:purch_node
  POd("Orden de Producción") class:prod_node
  space55::::hidden
  space56::::hidden
  space57::::hidden
  space58::::hidden

  %% Inter-row Connections 5-6
  SO -- "Entrega" --> DN class:sales_edge
  PO -- "Recepción" --> GRPO class:purch_edge
  POd -- "Producción" --> ITP class:prod_edge
  POd -- "Demanda" --> DP class:prod_edge,dashed_edge
  PRI -- "Afectación" --> FP class:fin_edge,dashed_edge

  %% Row 6: Fulfillment & Production Activity
  Lead("Lead") class:crmSRM_node
  DN("Nota de Entrega") class:sales_node
  GRPO("Recepción de Mercancías PO") class:purch_node
  ITP("Emisión a Producción") class:prod_node
  space65::::hidden
  space66::::hidden
  JE("Asientos Contables") class:fin_node
  space68::::hidden

  %% Inter-row Connections 6-7
  Lead -- "Conversion" --> CUS class:crmSRM_edge,dashed_edge
  DN -- "Factura" --> AR class:sales_edge
  GRPO -- "Factura" --> APc class:purch_edge
  ITP -- "Recibo" --> RFP class:prod_edge
  DN -- "Contable" --> FP class:fin_edge,dashed_edge
  GRPO -- "Contable" --> FP class:fin_edge,dashed_edge
  JE -- "Asiento" --> IAR class:fin_edge

  %% Row 7: Receipt from Production & Core Accounting
  BPM("Maestro de Socios de Negocios") class:crmSRM_node
  space72::::hidden
  space73::::hidden
  RFP("Recibo de Producción") class:prod_node
  space75::::hidden
  space76::::hidden
  space77::::hidden
  space78::::hidden

  %% Inter-row Connections 7-8
  RFP -- "Producto" --> SO class:prod_edge,dashed_edge
  RFP -- "Inventario" --> ITM class:prod_edge,dashed_edge
  RFP -- "Informes" --> PRR class:prod_edge
  BPM -- "Información" --> APAR class:crmSRM_edge,dashed_edge

  %% Row 8: Reporting / Analytical and Final Financial State
  SUP("Proveedor") class:crmSRM_node
  AR("Factura de Clientes") class:rep_node
  APc("Factura de Proveedores") class:rep_node
  space84::::hidden
  DP("Planificación de la Demanda") class:inv_node
  IAR("Informe de Auditoría de Inventario") class:fin_node
  FP("Registros Financieros") class:fin_node
  PRR("Informes de Producto") class:rep_node

  %% Inter-row Connections 8-9
  SUP -- "Compras" --> PO class:purch_edge,dashed_edge
  AR -- "Financiero" --> APAR class:fin_edge,dashed_edge
  APc -- "Financiero" --> APAR class:fin_edge,dashed_edge
  DP -- "Informes" --> BOR class:rep_node
  IAR -- "Conciliación" --> rec class:rep_node,dashed_edge
  FP -- "Asiento" --> JE class:fin_edge,dashed_edge

  %% Row 9: Payments & Secondary Reporting
  space91::::hidden
  inc("Pagos Recibidos") class:rep_node
  out("Pagos Emitidos") class:rep_node
  BOR("Informes de Pedidos Pendientes") class:rep_node
  space95::::hidden
  APAR("AP / AR") class:fin_node
  ABR("Informe de Saldos de Cuentas") class:rep_node
  rec("Conciliación") class:rep_node

  %% Inter-row Connections 9-10
  inc -- "Conciliación" --> APAR class:rep_edge,dashed_edge
  out -- "Conciliación" --> APAR class:rep_edge,dashed_edge
  APAR -- "Tesorería" --> CM class:fin_edge
  ABR -- "Conciliación" --> rec class:fin_edge,dashed_edge
  ABR -- "Informes" --> FR class:rep_edge

  %% Row 10: Cash Management & Main Financial Reporting
  space101::::hidden
  space102::::hidden
  space103::::hidden
  space104::::hidden
  space105::::hidden
  CM("Gestión de Tesorería") class:fin_node
  FR("Informes Financieros") class:rep_node
  space108::::hidden

  %% Inter-row Connections 10-11
  CM -- "Informes" --> FR class:fin_edge,dashed_edge
