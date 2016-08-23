# shinken-pack-linux-raid-by-ssh

## Description

This Shinken monitoring pack is used to check raid states over SSH.

This pack require nagios-plugins and nagios-plugins-contrib to work.

## Objects

### Templates

#### Host templates

* linux-raid-by-ssh: Manage all default thresholds and values for services

### Services

| Service name  | Description                          | Duplicate_foreach variable |
|---------------|--------------------------------------|----------------------------|
| RAID - $VALUE | Check RAID status for $VALUE$ plugin | _raid_plugins              |

## Default values

    _raid_plugins mtp
