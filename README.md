# GlueToolKits
A java executable program in daily work

## Pre-requirement
Java 8

## Functions
### Transform data format
#### 1. To blink numeric format: (support vcf(.vcf), hapmap(.hmp) and plink (.ped & .map) to Blink(.dat and .map)
        java -jar GTK.jar --file <file> --make-blink --out <outfile>
  
##### 2. To plink ped format: (suppport Blink(.dat & .map) to plink(.ped & .map)
        java -jar GTK.jar --file <ifle> --make-plink --out <outfile>
