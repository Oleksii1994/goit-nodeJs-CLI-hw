# CLI

This is a command line interface for reading list of contacts, getting contact by ID, adding new contact, deleting contact using contact's ID

## Available commands which you can use in the command line

To get the list of all contacts in table format:

```bash
node index.js --action="list"
```

![Screenshot of the output](https://monosnap.com/file/pNs7xYpRoo4Igbx7jfYOqjUjvo75Md/)

To get contact by Id:

```bash
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
```

![Screenshot of the output](https://monosnap.com/file/xWwAfH0w69ymYryglxm4VxN7Mntlhh)

To add new contact to the list of contacts:

```bash
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
```

![Screenshot of the output](https://monosnap.com/file/xpWakDVVSDUP7bOCRLLeyFSvtOQs3m)

To remove contact by Id:

```bash
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
```

![Screenshot of the output](https://monosnap.com/file/rG7Qoz9dPVjd2TWIP8oghrioE9vCgk)
