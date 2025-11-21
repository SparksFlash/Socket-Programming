# Socket-Programming

Socket-Programming — simple TCP/UDP socket examples and exercises for learning.

Collection of simple socket programming examples used for learning and demonstrations. Each `problem xx` folder contains a short project with server and client code (TCP/UDP) for specific exercises.

Structure
- `problem 01 FTP using/` — simple TCP/UDP file transfer examples.
- `problem 02 concurrent file server/` — concurrent file server and client.
- `problem 03 Remote Calculator/` — remote calculator server and client.
- `problem 04 streaming client and server/` — basic media streaming example.
- `problem 05 simple chatting/` — simple chat over TCP/UDP.
- `problem 06 multiple client – single server chatting/` — multi-client chat server.
- `problem 07  multicast chatting/` — multicast chat example.
- `problem 08 election vote casting/` — voting simulation script.

Usage

Each folder includes a `README.md` describing specific usage. Common patterns:

- Run a server (example):

```
python3 problem\ 01\ FTP\ using/tcp_ftp_server.py
```

- Run a client (example):

```
python3 problem\ 01\ FTP\ using/tcp_ftp_client.py
```

Notes
- These examples are intended for local testing and educational use only.
- Ensure you run server scripts before clients. You may need to run with sudo for multicast sockets on some systems.

Contributions

Feel free to open issues or submit pull requests to improve examples or add documentation.
