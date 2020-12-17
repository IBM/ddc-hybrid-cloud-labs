Use the IBM Cloud console to launch the OpenShift web console

![web console](../assets/generic/webconsole.png)

First create an 'Example Bank' namespace

![create project](../assets/generic/createproject.png)

From the navigation menu on the left select **Operators** --> **OperatorHub**

![operatorhub](../assets/generic/operatorhub.png)

Type 'Postgres' into the search bar, and select the **PostgreSQL Operator by Dev4Ddevs.com** tile.

![postgres operator](../assets/generic/postgresoperator.png)

Click **Continue** to show the community operator and then **Install**

![install operator](../assets/generic/installoperator.png)

Be sure you are installing the Operator in the `Example Bank` namespace, and click **Subscribe**

![subscribe](../assets/generic/subscribe.png)

Status will show "Succeeded: Up to date" when complete

![succeeded](../assets/generic/subscribe.png)
