# InstallNevstopPackage

How to Use it:

```
      - name: InstallNevstopPackage
        uses: NEVSTOP-LAB/InstallNevstopPackage@main
        with:
          LabVIEW_Version: 2017
          PackageName: LabVIEW-GlobalStop-Library
          NEVSTOP-FTP-IP: ${{ secrets.VIPM_FTP_IP }}
          NEVSTOP-FTP-PORT: ${{ secrets.VIPM_FTP_PORT }}
```
