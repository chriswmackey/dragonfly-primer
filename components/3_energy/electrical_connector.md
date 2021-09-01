# Electrical Connector

![](../../.gitbook/assets/Electrical_Connector.png)

![](../../.gitbook/assets/Electrical_Connector%20%281%29.png) - [\[source code\]](https://github.com/ladybug-tools/dragonfly-grasshopper/blob/master/dragonfly_grasshopper/src//DF%20Electrical%20Connector.py)

Create an OpenDSS Electrical Connector from its linear geometry and the wires carried along it.

## Inputs

* **geo \[Required\]**

  A line or polyline representing an Electrical Connector. 

* **wires \[Required\]**

  A list of text for the wires carried along the electrical connector, which will be looked up in the Wires library \(the output from the "DF OpenDSS Libraries" component\). This can also be a list of custom Wire objects. 

* **name**

  Text to set the base name for the Electrical Connector, which will also be incorporated into unique ElectricalConnector identifier. If the name is not provided, a random one will be assigned. 

## Outputs

* **connector**

  A Dragonfly Electrical Connector object that can be used within an Electrical Network. 
