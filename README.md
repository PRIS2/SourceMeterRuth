# SourceMeterRuth - Apache Jakarta
<p align="center"><a><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Apache_Software_Foundation_Logo_%282016%29.svg/1200px-Apache_Software_Foundation_Logo_%282016%29.svg.png" align="center" width="600"></a></p>

Las versiones de Apache Jarkarta utilizadas han sido:
- **jakarta-ant-1.1**: https://archive.apache.org/dist/ant/source/jakarta-ant-1.1.zip
- **jakarta-ant-1.2**: https://archive.apache.org/dist/ant/source/jakarta-ant-1.2-src.zip
- **jakarta-ant-1.3**: https://archive.apache.org/dist/ant/source/jakarta-ant-1.3-src.zip

## Importante para la utilización de SourceMeter
### Instalación de Java 11
Esto lo realizamos con las siguientes líneas en el Simbolo del sistema de Windows.

```
set "JAVA_HOME=C:\Program Files\Java\jdk-11.0.13"
set "PATH=%ANT_HOME%\bin;%JAVA_HOME%\bin;%M2_HOME%\bin;%PATH%"
```
### Ejecutar un proyecto
Ejecutar un proyecto es tan sencillo como escribir dentro del Simbolo del sistema y desde la carpeta donde esta el .exe del SourceMeter (SourceMeterJava.exe) el siguiente comando:

```
SourceMeterJava -projectName=MyProject -projectBaseDir=MyProjectDir -resultsDir=Results -runFB=true -FBFileList=filelist.txt
```
Un ejemplo real de uno de mis casos [jakarta-ant-1.3] ha sido:
```
SourceMeterJava -projectName=Apache1.3 -projectBaseDir=C:\Users\tiaru\Desktop\SourceMeter-10.0.0-x64-Windows\Java\Apache1.3\jakarta-ant-1.3 -resultsDir=C:\Users\tiaru\Desktop\SourceMeter-10.0.0-x64-Windows\Java\Apache1.3 -runFB=true -FBFileList=apache1_3.txt
```
