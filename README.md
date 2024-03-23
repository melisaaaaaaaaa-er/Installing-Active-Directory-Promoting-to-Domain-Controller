# Installing Active Directory, Promoting to Domain Controller

<h2>Deployment and Configuration:</h2>

<h3>Installing Active Directory on DC-1</h3>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/10.png"/>

On DC-1, select the “Add Roles and Features” on the Server Manager.

Follow the screenshots below to make the appropriate configurations. Click “Next” for those not specified.

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/11.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/12.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/13.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/14.png"/>

<h3>Promoting DC-1 to Domain Controller</h3>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/15.png"/>

Once AD has been installed on the server, the option to promote it to Domain Controller will pop up in the top-right corner.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/16.png"/>

Give the domain a new forest and give it a name in the scheme of -name-.-suffix-. This can be anything.

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/17.png"/>

Assign a password.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/18.png"/>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/19.png"/>

Once the Domain Controller features have installed the machine will restart.

When logging back in, you must log in within the domain – add the domain name before the username you are trying to log in with.
