# sap-cap-bookshop
SAP CAP 



```
npm i -g @sap/cds-dk

cds init bookshop
cd bookshop
cds add samples,hana,mta

npm i mbt

mbt build

```

### Deployment

cf login --sso

cf deploy mta_archives/<>.mtar
