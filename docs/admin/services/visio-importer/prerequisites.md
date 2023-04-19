# Prerequisites for using the Visio Importer

To use the Visio Importer with a storage, it must be registered in the Operations Service by the Operations Team. For the registration the `storage tenant ID`, `company ID`, `URL to the storage` and a `REST Api token` (with at least `Architect` permissions) need to be provided. To use the importer, users have to log in via the Auth Service. The company ID provided during storage registration will be used to match with the Auth Service user(s) and to determine if the role the user has in the company is sufficient (as of now, the `Admin` role is required).