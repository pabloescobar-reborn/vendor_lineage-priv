## Cloning Vendor Lineage-Priv Repository

To clone the vendor Lineage-Priv repository, run:

```bash
git clone https://github.com/pabloescobar-reborn/vendor_lineage-priv vendor/lineage-priv
```
# Add in device.mk file
```make
$(call inherit-product, vendor/lineage-priv/keys/keys.mk)
