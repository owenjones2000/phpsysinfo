# phpsysinfo
#### Introduction and use of the package
```
use Justfine\PhpSysInfo\SystemInformation;

        $sysinfo = new SystemInformation;
        dump($sysinfo->getMemoryUsage());
        dump($sysinfo->getMemoryTotal());
        dump($sysinfo->getCpuInfo());
        dump($sysinfo->getUptime());
        dump($sysinfo->getLoadAverages());
        dump($sysinfo->getDistribution());
        dump($sysinfo->getKernel());
        dump($sysinfo->getLoadPercent());
        dump($sysinfo->getStorageTotal());
        dump($sysinfo->getStorageFree());
        dump($sysinfo->getStorageUsage());
         .....
```