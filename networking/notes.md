# Networking Commands Lab

## Objective

Learn how to identify network configuration, test connectivity, verify DNS resolution, and troubleshoot networking issues in Linux.

## Commands Used

### Check IP Address

```bash
ip addr
```

Purpose:
Display network interfaces and assigned IP addresses.

### Check Routing Table

```bash
ip route
```

Purpose:
Display network routes and default gateway.

### Test Connectivity

```bash
ping google.com
```

Purpose:
Verify network connectivity with a remote host.

### DNS Resolution

```bash
nslookup google.com
```

Purpose:
Convert a domain name into its corresponding IP address.

### View Open Ports

```bash
ss -tulnp
```

Purpose:
Display listening ports and associated services.

### Test HTTP Connectivity

```bash
curl https://google.com
```

Purpose:
Verify website and API accessibility.

### Check Hostname

```bash
hostname
```

Purpose:
Display the system hostname.

### View Network Interfaces

```bash
ip link
```

Purpose:
Display available network interfaces.

## Key Learnings

- Every network-connected device has an IP address.
- DNS converts domain names into IP addresses.
- Ping helps verify connectivity between systems.
- Routing tables determine where network traffic is sent.
- Open ports indicate services available on the system.
- Curl is useful for testing websites and APIs.
- Network interfaces provide connectivity to networks.

## Real DevOps Usage

- Troubleshoot application connectivity issues
- Verify DNS configuration
- Check server reachability
- Test APIs and web applications
- Verify service ports
- Diagnose network problems
- Monitor infrastructure connectivity
