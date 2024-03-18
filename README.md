# Virtual Earth(VE)

# Introduction
A project about deploying and managing the Virtual Earth (not seriously)

If the project is helpful, give me a star please~

**Purpose of Use: All resources contained within this folder and its sub-directories are strictly for study and research purposes. They are intended to provide reference and materials for academic and research personnel. No other purposes are sanctioned.**
**Non-commercial and Illegal Usage: The utilization of this folder and its contents for any commercial or illegal purposes is strictly prohibited. Users will bear full responsibility for any legal consequences arising from violations of this provision.**

---

# Install & Update
System Supported: **HumanBrain:latest**

## Install Daydream
This project is based on Daydream. If you have installed this package, just skip.
```
package install human/daydream:latest
```
or install desire version
```
package install human/daydream:1.0
```

### Update
```
package update human/daydream -force
```

## Install VE
```
package install steven/ve:latest
```

---

# Run
## Start Daydream
```
package run daydream
```

Check statue
```
daydream statue
```

Full commands
```
daydream help
```
## Start VE
Recommended action before starting:
```
body part eye close -both
```

Run:
```
package run ve
```

Check statue
```
ve statue
```

Full commands
```
ve help
```

If 'Running...' text is shown in the return info, the VE is successfully running

---

# Q & A

**I can't install the ve successfully!!!!!Help me plase!!!!**

A: You can clear the cache and restart the Daydream and VE ``package restart daydream`` ``package restart ve`` or refresh the system ``body part eye close -both`` ``body action sleep 1h`` ``body part eye open -both``

**I don't konw why I should submit this issuse!**

A: ``body shutdown``

# Pr
You can add some commands in usage.md, just follow the format ``ve <action> <detail> <...>``, like ``ve create <thing> <x><y><z>`` ``ve import xxx.vewd`` ``ve set time <...>``

