# 👔 HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

## 📘 Salesforce CRM Documentation

---

## 🔍 **Project Overview**

**HandsMen Threads** is a customized Salesforce CRM solution designed specifically for a luxury men’s fashion brand. This system automates essential operations like order tracking, customer loyalty, inventory oversight, and marketing campaign management through a combination of Salesforce’s point-and-click tools and advanced Apex programming.

---

## 🎯 **Objectives**

* Streamline processes such as order confirmations and loyalty program updates
* Boost operational performance across Sales, Inventory, and Marketing departments
* Reduce manual data entry errors using automation and field validations
* Deliver real-time, scalable insights for business decision-making

---

## 🧩 **Salesforce Implementation**

### ✅ **Custom Objects**

* **HandsMen\_Customer\_\_c**: Manages customer details, preferences, and loyalty levels
* **HandsMen\_Product\_\_c**: Holds product information including pricing, size, and stock status
* **HandsMen\_Order\_\_c**: Represents customer orders linked with products and current status
* **Inventory**: Monitors available stock, warehouse data, and replenishment alerts
* **Marketing\_Campaign\_\_c**: Stores campaign details such as type, schedule, and audience segments

---

## 🗂️ **Tabs & App**

* **Tab:** HandsMen Customer – quick navigation to customer records
* **App:** HandsMen Threads – unified Lightning App for all CRM components

---

## 🧾 **Fields Summary**
| **Object**             | **Key Fields**                                                                                                                          |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **HandsMen Customer**  | Name (Record Name), Email (Email), Phone (Phone), Loyalty\_Status\_\_c (Picklist: Bronze, Gold, Silver), Total\_Purchases\_\_c (Number) |
| **HandsMen Product**   | Name (Record Name), SKU (Text), Price (Currency), Stock\_Quantity\_\_c (Number)                                                         |
| **HandsMen Order**     | Order\_Number (Record Name), Status (Picklist: Pending, Confirmed, Rejection), Quantity\_\_c (Number), Total\_Amount\_\_c (Number)      |
| **Inventory**          | Auto Number (Record Name), Warehouse (Text), Stock\_Quantity\_\_c (Number)                                                              |
| **Marketing Campaign** | Campaign\_Name (Record Name), Start\_Date (Date), End\_Date (Date)                                                                      |


## 🛡️ **Security & Access**

* **Profiles:** Sales Profile – provides limited access to relevant objects
* **Roles:** Includes roles for Sales, Inventory Manager, and Marketing Manager
* **Permission Sets:** `Permission_Platform_1` – grants additional access to restricted fields and objects
* **Sample Users:** Niklaus, Kol, Loretta Daniel – represent different team members for testing and demo purposes

---

## 📧 **Email Templates & Alerts**

* **Order Confirmation:** Dispatched to customers upon order success
* **Loyalty Notification:** Informs customers about changes in loyalty status
* **Low Stock Alert:** Notifies inventory managers when stock falls below a threshold
* **Automation Alerts:** Triggered automatically by Flow-based processes

---

## 🔄 **Flows**

* **Stock Alert Flow:** Monitors inventory and sends alerts for low stock items
* **Loyalty Status Flow:** Evaluates order history and updates loyalty tiers
* **Order Confirmation Flow:** Sends an order confirmation email right after creation

---

## ⚙️ **Apex Automation**

* **OrderTriggerHandler:** Apex class containing the logic for order operations
* **OrderTrigger:** Executes business logic on creation/update of `HandsMen_Order__c`
* **InventoryBatchJob:** Scheduled Apex batch job that scans inventory and manages restocking alerts
* **Scheduled Job:** Automates execution of `InventoryBatchJob` at regular intervals

---

## 🚀 **Deployment & Versioning**

* Project managed and deployed via **Salesforce CLI** using the **SFDX** development model
* Source-controlled through **Git** and synchronized with **GitHub** for team collaboration

---

## ✅ **Conclusion**

HandsMen Threads CRM is a smart, automated Salesforce solution tailored for high-end fashion retailers. It simplifies operations, enhances customer loyalty, and ensures inventory accuracy—all within a scalable, Lightning-powered environment. The platform reflects a modern digital transformation strategy for retail excellence.



---

### 👨‍💻 Developer & Contact  
**Name**: Sai Praneetha D  
**Email**: 224g1a3279@srit.ac.in  
**Role**: Salesforce Developer  
**Project Status**: ✅ Completed  
