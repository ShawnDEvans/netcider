#NetCider
Calculates network segments based on CIDR notation. It's a pretty handy utility for pen testers. You provide a CIDR range and this tool will output network statistics, or the complete IP range, which can then be fed to tools that don't support CIDR notation.

```
=============================================================
==================== Net Cider v1.0 beta ====================
======================== Shawn Evans ========================
================ Shawn.Evans@Knowledgecg.com ================
=============================================================

-o      Output full IP range to stdout

Example:
$ python netCider.py 192.168.0.2/24
$ python netCider.py -o 192.168.0.2/24
```
