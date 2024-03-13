# Installing Active Directory, Promoting to Domain Controller

<h2>Deployment and Configuration:</h2>

<h3>Installing Active Directory on DC-1</h3>

![10](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/52353a85-c0de-4c0a-b9d3-8422e71f3c71)

On DC-1, select the “Add Roles and Features” on the Server Manager.

Follow the screenshots below to make the appropriate configurations. Click “Next” for those not specified.

![11](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/2e43b8c4-2b96-4654-b3d0-0d7cc6992dad)

![12](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/0d6500ce-6311-45a7-a50a-8067d3ce89f3)

![13](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/339ab260-59e7-4ca1-869f-ba1bc7312320)

![14](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/7ea5efc4-b22c-4232-815c-9fb8b6d23889)

<h3>Promoting DC-1 to Domain Controller</h3>

![15](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/d8599537-0c8e-47ac-980e-da43bf461144)

Once AD has been installed on the server, the option to promote it to Domain Controller will pop up in the top-right corner.

#
![16](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/f90458ad-1732-4ced-a189-734daeed550c)

Give the domain a new forest and give it a name in the scheme of -name-.-suffix-. This can be anything.

![17](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/29e00bc4-c764-4638-9f47-aa5ba290be80)

Assign a password.

#
![18](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/06d86da4-26be-4358-aa5f-03fa15db0c8b)

![19](https://github.com/melisa-er/Installing-Active-Directory-Promoting-to-Domain-Controller/assets/157723219/6756eea9-509b-4517-ba84-1ae9a2b5a1e5)

Once the Domain Controller features have installed the machine will restart.

When logging back in, you must log in within the domain – add the domain name before the username you are trying to log in with.
