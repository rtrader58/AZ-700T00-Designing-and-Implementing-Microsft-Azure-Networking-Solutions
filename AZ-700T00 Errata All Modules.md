# AZ-700T00 Designing and Implementing Microsft Azure Networking Solutions  - Errata All Modules <br>
 
## Module 1 – Introduction to Azure virtual networks (Total Time ~70 Minutes) <br>

### M01-Unit 4 Design and implement a Virtual Network in Azure (~25 Min) <br>

### Required Lab Setup <br>

Prepare cloud shell for later use <br>
Step 5:  Use the resource group that is auto populated <br>

When creating the virtual networks delete the existing IP range <br>

### M01 - Unit 6 Configure DNS settings in Azure (~ 25 Min) <br>

Task 4: Verify records are present in the DNS zone <br>
Exercise - Connect to the Test VMs using RDP <br>
After step 19 disconnect from both RDP sessions <br>

### M01 - Unit 8 Connect two Azure Virtual Networks using global virtual network peering (~20 Min) <br>

No errata

## Module 2 – Design and implement an identity hybrid networking <br>

### M02 - Unit 3 Create and configure a virtual network gateway (~70 Min) <br>

Task 1:  Create CoreservicesVnet and ManufacturingVnet <br>
Step 1:  If required use advanced settings to create a storage account <br>

# Complete tasks 6 and 7 before taking a break <br>

Task 6: Create CoreServicesVnet Gateway <br>
Step 3:  If Public IP Address Type is greyed out continue <br>
Continue with Task 7 while Gateway is being built. <br>

Task 7: Create ManufacturingVnet Gateway <br>
Step 3:  If Public IP Address Type is greyed out continue <br>
Routinely click in the Azure Portal so the lab does not end on you <br>
Both Virtual Gateways have to finish building before continuing to Task 8 <br>

Task 10: Verify that the connections connect <br>
Step 2:  it took 10 minutes after gateways were finished building before status showed connected <br>

### M02 - Unit 7 Create a Virtual WAN by using Azure Portal (~65 Min)

No errata <br>

## Module 3 – Design and Implement Azure ExpressRoute <br>

Throughout the lab use the search box to search for ExpressRoute Circuits <br>

When cleaning up the lab you will need to create a storage account, use advanced setting to create the storage account <br>

## Module 4 -Load balance non-HTTP(S) traffic in Azure <br>

### Exercise:  Create and configure an Azure load balancer <br>

Task 2:  Create backend servers <br>
Step 1:  if prompted use advance setting to create a storage account <br>

## Module 5 – Load balance HTTP(S) traffic in Azure <br>

### Exercise:  Deploy Azure Application Gateway <br>

Task 1:  Create an application gateway <br>
You will need to give the Application Gateway a Priority when configuring the listener.  Set it to 100 <br>

Task 2:  Create virtual machines <br>
Step 1:  if prompted use advance setting to create a storage account <br>

## Module 6 – Design and implement network security <br>

### Exercise:  Configure DDos Protection on a virtual network using the Azure portal <br>

Task 6:  Configure DDos Alerts <br>
Step 3:  You will need to select all images the in the Marketplace choose the correct image <br>
Step 3:  You will need to select all sizes, you may have to search for the B1ls size <br>
Step 7:  After downloading the key, select return to creating virtual machine <br>

Task 7:  Submit a DDoS service request to run a DDoS attack <br>
Step 1:  When creating the breakingpoint account you will need to use a valid email address that you have access to (Recommend creating a dummy outlook account) <br>

Task 8:  Clean up resources <br>
Step 1:  if prompted create a storage account <br>

### Exercise:  Deploy and configure Azure Firewall using the Azure Portal <br>

Task 4: Deploy the firewall and firewall policy <br>
Step 1:  Use the Search resources box at the top of the Azure portal instead of create a resource <br>

Task 7:  Configure a network rule <br>
Wait until the Application rule has deployed <br>

Task 8:  Configure a Destination NAT (DNAT) rule <br>
Wait until the Network rule has deployed <br>

### Exercise:  Secure your virtual hub using Azure Firewall Manager <br>

Task 2:  Create the secured virtual hub <br>
Step 3:  Under Deployments, select Virtual Hubs <br>

Task 4: Deploy the servers <br>
Wait until the Task 3 completes <br>

Task 5:  Create a firewall policy and secure your hub <br>
Step 2:  Under Security, select Azure Firewall Policies <br>

Task 6:  Associate the firewall policy <br>
Wait for Task 5 to complete before moving on <br>
Step 4:  Manage associations is located on the top bar <br>

Association took over 15 minutes <br>

## Module 7 – Design and implement private access to Azure services <br>

### Exercise:  Restrict network access to PAAS resources with virtual network service endpoints <br>

Task 4:  Add additional outbound rules <br>
Step 2:  Enter Any for the source <br>

Task 5:  Allow access for RDP connections <br>
Step 3:  Choose Any for Destination <br>

Task 7: Create a file share in the storage account <br>
Step 1:  Option to searching is to Go to resource after completion <br>

Task 8: Restrict network access to a subnet <br>
Step 2:  Select Enable from selected networks and IP addresses <br>
Step 8:  Copy the key to notepad <br>

Task 9: Create virtual machines <br>
Step 1:  Create a Storage account if needed <br>

### Exercise - Create an Azure Private Endpoint using Azure PowerShell <br>

Task 2: Create a virtual network and bastion host <br>
Note:  It took ~20 Minutes to deploy the Bastion <br>

Task 3: Create a test virtual machine <br>
Copy the script into notepad <br>
Either copy / paste or type the $Cred command <br>
When prompted enter the credentials <br>

Student <br>
Pa55w.rd1234 <br>

Copy and paste the remaining script into the cloud shell <br>

## Module 08 (CSS): Design and implement network monitoring <br>

### Exercise – Monitor a load balancer resource using Azure Monitor <br>

Task 3: Create a backend pool <br>
Step 4: click save <br>

Task 4: Create a health probe <br>
Step 1: From the myIntLoadBalancer page of your load balancer, under Settings, click Health probes, then click Add. <br>
Step 2:  On the Add health probe page, enter the information from the table below.  Ignore Unhealthy Threshold Setting <br>

Task 5: Create a load balancer rule <br>
Step 1: From the myIntLoadBalancer page of your load balancer, under Settings, click Load balancing rules, then click Add. <br>

Task 6: Create backend servers <br>
Step 1:  if prompted create a storage account <br>

Task 7: Add VMs to the backend pool <br>
Step 3:  Under IP configuration select +Add <br>

Task 8: Install IIS on the VMs <br>
Step 5:  Select the Popup blocker on the address bar choose to allow and select done <br>

Click Connect <br>

Task 9: Test the load balancer <br>
Connect to the test VM to test the load balancer <br>
Step 10:  Click on Edge icon in the task bar to open the web browser <br>

Task 13: View resource health <br>
Step 1:  Search for Monitor if not shown <br> 