# sap-sql  
sap-sql は、主にエッジアプリケーションにおいて、SAPと連携されたデータを保存するSQLデータベースを作成するためのレポジトリです。
sap-sql は、そのままクラウド環境におけるアプリケーションにも、適用可能です。  
本レポジトリに含まれるsqlファイルの適用により、空の（＝テーブルの無い）データベースが作成されます。  
データベース内にテーブルを作成する際には、下記のリストを参照し、適宜、必要なテーブルを追加してください。  

## sap-sql データベース に 定義される SAP関連テーブル の所在
本レポジトリを参照して作成されたデータベース 内に SAP関連テーブル を定義する際には、下記を参照してください。  

### Central Functions

* [sap-classification-sql](https://github.com/latonaio/sap-classification-sql)
* [sap-characteristic-sql](https://github.com/latonaio/sap-characteristic-sql)
* [sap-bank-master-sql](https://github.com/latonaio/sap-bank-master-sql)
* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)

### Logistics  

* [sap-product-group-sql](https://github.com/latonaio/sap-product-group-sql)  
* [sap-product-master-sql](https://github.com/latonaio/sap-product-master-sql)  
* [sap-product-master-class-sql](https://github.com/latonaio/sap--product-master-class-sql) 
* [sap-batch-master-record-sql](https://github.com/latonaio/sap-batch-master-record-sql)  

### Inventory Management  

* [sap-material-stock-sql](https://github.com/latonaio/sap-material-stock-sql)  
* [sap-reservation-document-sql](https://github.com/latonaio/sap-reservation-document-sql)  
* [sap-inbound-delivery-sql](https://github.com/latonaio/sap-inbound-delivery-sql)
* [sap-material-document-sql](https://github.com/latonaio/sap-material-document-sql)
* [sap-physical-inventory-document-sql](https://github.com/latonaio/sap-physical-inventory-document-sql)
* [sap-warehouse-resource-sql](https://github.com/latonaio/sap-warehouse-resource-sql)

### Sales Management

* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)  
* [sap-credit-management-master-sql](https://github.com/latonaio/sap-credit-management-sql)
* [sap-customer-material-sql](https://github.com/latonaio/sap-customer-material-sql)  
* [sap-sales-pricing-sql](https://github.com/latonaio/sap-sales-pricing-sql)  
* [sap-sales-inquiry-sql](https://github.com/latonaio/sap-sales-inquiry-sql)
* [sap-sales-quotation-sql](https://github.com/latonaio/sap-sales-quotation-sql)
* [sap-sales-order-sql](https://github.com/latonaio/sap-sales-order-sql)  
* [sap-sales-contract-sql](https://github.com/latonaio/sap-sales-contract-sql)
* [sap-sales-scheduling-agreement-sql](https://github.com/latonaio/sap-sales-scheduling-agreement-sql)
* [sap-outbound-delivery-sql](https://github.com/latonaio/sap-outbound-delivery-sql)  
* [sap-customer-return-sql](https://github.com/latonaio/sap-customer-return-sql)  
* [sap-billing-document-sql](https://github.com/latonaio/sap-billing-document-sql)  
* [sap-credit-memo-request-sql](https://github.com/latonaio/sap-credit-memo-request-sql)
* [sap-debit-memo-request-sql](https://github.com/latonaio/sap-debit-memo-request-sql)

### Procurement Management

* [sap-business-partner-sql](https://github.com/latonaio/sap-business-partner-sql)
* [sap-purchasing-source-list-sql](https://github.com/latonaio/sap-purchasing-source-list-sql)  
* [sap-purchasing-info-record-sql](https://github.com/latonaio/sap-purchasing-info-record-sql) 
* [sap-purchase-requisition-sql](https://github.com/latonaio/sap-purchase-requisition-sql) 
* [sap-purchase-order-sql](https://github.com/latonaio/sap-purchase-order-sql)
* [sap-purchase-contract-sql](https://github.com/latonaio/sap-purchase-contract-sql)
* [sap-purchase-scheduling-agreement-sql](https://github.com/latonaio/sap-purchase-scheduling-agreement-sql)
* [sap-supplier-invoice-sql](https://github.com/latonaio/sap-supplier-invoice-sql)

### Production Management  

* [sap-bill-of-material-sql](https://github.com/latonaio/sap-bill-of-material-sql)  
* [sap-bill-of-material-where-used-list-sql](https://github.com/latonaio/sap-bill-of-material-sql) 
* [sap-work-center-sql](https://github.com/latonaio/sap-work-center-sql)  
* [sap-production-routing-sql](https://github.com/latonaio/sap-production-routing-sql)  
* [sap-material-planning-data-sql](https://github.com/latonaio/sap-material-planning-data-sql)  
* [sap-planned-independent-requirement-sql](https://github.com/latonaio/sap-planned-independent-requirement-sql)  
* [sap-planned-order-sql](https://github.com/latonaio/sap-planned-order-sql)
* [sap-production-order-sql](https://github.com/latonaio/sap-production-order-sql)   
* [sap-production-order-confirmation-sql](https://github.com/latonaio/sap-production-order-confirmation-sql)  


### Process Management 

* [sap-master-recipe-sql](https://github.com/latonaio/sap-master-recipe-sql) 
* [sap-process-order-sql](https://github.com/latonaio/sap-process-order-sql)
* [sap-process-order-confirmation-sql](https://github.com/latonaio/sap-process-order-confirmation-sql)

### Quality Management  

* [sap-inspection-plan-sql](https://github.com/latonaio/sap-inspection-plan-sql) 
* [sap-quality-info-record-sql](https://github.com/latonaio/sap-quality-info-record-sql) 

### Plant Maintenance  

* [sap-functional-location-sql](https://github.com/latonaio/sap-functional-location-sql)
* [sap-equipment-master-sql](https://github.com/latonaio/sap-equipment-master-sql)  
* [sap-equipment-hierarchy-sql](https://github.com/latonaio/sap-equipment-hierarchy-sql)  
* [sap-maintenance-bill-of-material-sql](https://github.com/latonaio/sap-maintenance-bill-of-material-sql)
* [sap-maintenance-plan-sql](https://github.com/latonaio/sap-maintenance-plan-sql)
* [sap-maintenance-item-sql](https://github.com/latonaio/sap-maintenance-item-sql)
* [sap-maintenance-notification-sql](https://github.com/latonaio/sap-maintenance-order-confirmation-sql)
* [sap-maintenance-order-sql](https://github.com/latonaio/sap-maintenance-order-sql)
* [sap-maintenance-order-confirmation-sql](https://github.com/latonaio/sap-maintenance-order-confirmation-sql)
* [sap-defect-sql](https://github.com/latonaio/sap-defect-sql)
* [sap-maintenance-task-list-sql](https://github.com/latonaio/sap-maintenance-task-list-sql)
* [sap-measuring-point-sql](https://github.com/latonaio/sap-measuring-point-sql)
* [sap-measurement-document-sql](https://github.com/latonaio/sap-measurement-document-sql)

### Customer Service

* [sap-service-order-sql](https://github.com/latonaio/sap-service-order-sql)
* [sap-service-confirmation-sql](https://github.com/latonaio/sap-service-confirmation-sql)


## Kubernetes 上での Pod の立ち上げ、データベースの作成、テーブルの作成などの方法  
Kubernetes 上での Pod の立ち上げ、データベースの作成、テーブルの作成などの方法については、[mysql-kube](https://github.com/latonaio/mysql-kube) を参照してください。  


