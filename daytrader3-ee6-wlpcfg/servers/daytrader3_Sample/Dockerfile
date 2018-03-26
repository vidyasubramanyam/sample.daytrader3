FROM websphere-liberty:kernel
COPY server.xml /opt/ibm/wlp/usr/servers/defaultServer/
COPY daytrader3-ee6.ear /opt/ibm/wlp/usr/servers/defaultServer/dropins/
COPY derby-10.10.1.1.jar /opt/ibm/wlp/usr/shared/resources/Daytrader3SampleDerbyLibs/
RUN installUtility install --acceptLicense defaultServer
