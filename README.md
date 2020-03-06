# Ground Robot Motor Driver Configuration

The RoboteQ specific motor controller configuration for boarAI, a caterpillar based UGV.
The motor controller is a slave system connected via Modbus to an APU main controller.

Actual Controller Model [FBL2360TE](https://www.roboteq.com/index.php/component/virtuemart/424/fbl2360e-424-detail?Itemid=971)

## Modbus Setup

[RoboteQ Modbus Implementation Documentation](https://www.roboteq.com/index.php/technology-menu/408-modbus-roboteq-implementation)

**Node IDs:**


| broadcast   | 0 |
|-------------|---|
| APU (master)| ? |
| FBL (slave) | 1 |


**Network:**

APU ip: 192.168.1.1

FBL ip: 192.168.1.20

Subnet: 255.255.255.0

protocol: Modbus TCP

port: 502
