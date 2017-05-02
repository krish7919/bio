## Aspirations
* Opensource contributor, blogger & polyglot programmer
* Interest in learning & applying my knowledge - from low level kernel tweaking to cluster level optimizations - to build modern distributed systems
* Championing the cause of writing tests with code, CI/CD, fast prototyping
* Strive to write code that is clean, commented/documented, testable, maintainable


## Summary
* 5 years in software engineering, with 2.5+ years in analyzing, designing, implementing, troubleshooting, and operating a big data pipeline, as a cross-data center distributed system using microservices. Possess an in-depth knowledge of backend architecture required for modern web-scale applications.
* Repeatedly recognized as fast learner and executor, meeting critical deadlines by managing technical debt effectively.
* Practitioner of agile methodology and test driven development.
* Well-informed with emerging and disruptive technologies, leveraging them to improve current systems.
<table>
  <tr>
    <td colspan="2">Technologies</td>
  </tr>
  <tr>
    <td colspan="2"><b>Cluster management</b>: &nbsp;&nbsp;&nbsp;Kubernetes, Mesos, Aurora, Zookeeper, Docker, Bosun, cAdvisor</td>
  </tr>
  <tr>
    <td><b>Messaging Systems</b>: Apache Kafka</td>
    <td><b>Data stores</b>: Apache Cassandra, etcd</td>
  </tr>
  <tr>
    <td><b>Data Processing</b>: Apache Storm, Apache Spark</td>
    <td><b>Security</b>: OpenVPN, EasyRSA-based PKI</td>
  </tr>
  <tr>
    <td><b>Serialization Frameworks</b>: Protobuf, Thrift</td>
    <td><b>Networking</b>: Opendaylight, flannel, HAProxy</td>
  </tr>
  <tr>
    <td><b>Operating Systems</b>: Linux (Ubuntu, CoreOS)</td>
    <td><b>Languages</b>: Golang, Java, Scala, Python, Perl, C</td>
  </tr>
  <tr>
    <td><b>Public Cloud Platforms</b>: EC2, GCE, Azure</td>
    <td><b>Tools</b>: Eclipse, Git, Maven, Travis</td>
  </tr>
</table>


## Employment History
<table>
  <tr>
    <td>Decentralized Systems Engineer</td>
    <td>BigchainDB GmbH</td>
    <td>Dec 2016 onwards</td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
          <td>Primary engineer responsible for ‘productionising’ the BigchainDB software.</td>
        </tr>
        <tr>
          <td>Dockerized various modules, designed and configured the cluster for high availability.</td>
        </tr>
        <tr>
          <td>Implemented TLS connectivity and DoS mitigation strategy.</td>
        </tr>
        <tr>
          <td>Visit <a href="http://bigchaindb.com">bigchaindb.com</a> and <a href="http://ipdb.foundation">ipdb.foundation</a></td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>Member of Technical Staff</td>
    <td>Ionos Networks/IP Core Solutions</td>
    <td>May 2014 - Nov 2016</td>  
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
          <td><b>Supply Side Platform and Ad Exchange Network</b></td>
        </tr>
        <tr>
          <td>Developed SSP service from scratch as per the OpenRTB specification.</td>
        </tr>
        <tr>
          <td>Extended the OpenRTB specification to add custom functionality for our specific use case, with a particular
focus on private marketplace transactions.</td>
        </tr>
        <tr>
          <td>Designed it to send bid request to multiple Demand Side Platforms, collate the bid responses, and find a bid
winner in real time.</td>
        </tr>
        <tr>
          <td>Implemented in Golang.</td>
        </tr>
        <tr>
          <td><b>Custom Communication Protocol for a Large-Scale Distributed System</b></td>
        </tr>
        <tr>
          <td>Helped design and develop a custom protocol for communication between a distributed system spread
          across multiple datacenters.</td>
        </tr>
        <tr>
          <td>Used binary encoding for headers, with message payloads defined using protobuf.</td>
        </tr>
        <tr>
          <td>Implemented in C, Golang, Java, Scala, Python.</td>
        </tr>
        <tr>
          <td><b>OpenDaylight Kafka Southbound Plugin</b></td>
        </tr>
        <tr>
          <td>Developed a proprietary southbound plugin in OpenDaylight SDN controller to communicate with various network services using Apache Kafka as a shared message bus.</td>
        </tr>
        <tr>
          <td>Implemented in Java.</td>
        </tr>
        <tr>
          <td><b>OpenDaylight Discovery Plugin</b></td>
        </tr>
        <tr>
          <td>Implemented a custom discovery module in OpenDaylight SDN controller for discovering custom network devices in our data plane, and cache the resultant network topology.</td>
        </tr>
        <tr>
          <td>Implemented in Java.</td>
        </tr>
        <tr>
          <td><b>Stream Analytics</b></td>
        </tr>
        <tr>
          <td>Designed and developed a complex topology in Apache Storm for real time processing and dispatch of events to appropriate services.</td>
        </tr>
        <tr>
          <td>Parallelized multiple, mutually exclusive operations, optimizing the data processing pipeline.</td>
        </tr>
        <tr>
          <td>Implemented the Storm topology in Java.</td>
        </tr>

Batch Analytics
● Developed batch analytics jobs using Apache Spark to perform hourly trend analysis on dataset stored in
Apache Cassandra to gain insight about network characteristics between various endpoints over different
types of links.
● Implemented in Scala, Python and Golang

IoT Sensor Network
● Part of the team that built an IoT sensor network for data gathering from scratch.
● Involved with capture and analysis of wireless packets using tools like airodump­ng, tcpdump, wireshark,
flashing the sensor devices and configuring long running services on the device.
● Implemented in Python.


Custom software upgrade workflow
● Designed and implemented an update mechanism to check for and download new software packages on
low­speed, high­latency network connection, with features like download resumption from point of failure,
rollback, caching, and retry protocols.
● Implemented in Python.


Docker Volume Plugin for AWS EFS
● Designed and implemented a customized docker volume plugin using the plugin support in docker for
persisting container data across a cluster, which ensures that if an application dies/quits and is rescheduled
elsewhere in the cluster, a containerized service can restore state before proceeding further.
● Implemented in Golang.

Cluster Management for Big Data Pipeline
● Architected & implemented an auto­scaling, cluster management solution from scratch, helping engineers
focus on business logic rather than scale issues, with monitoring giving insight into entire cluster state.
● Tech stack: CoreOS, Ubuntu, etcd, flannel, docker, Mesos, Aurora, Bosun, cAdvisor, HAProxy, confd, Kafka,
Cassandra, Storm, Spark, AWS EC2.
● Implemented in Golang, Bash, Python.

Secure Tunnel Overlay Network
● Developed a secure network connectivity between various sub­systems/micro­services using OpenVPN.
● Designed and developed an API­driven certificate authority service for dynamic certificate signing request
authentication, certificate generation and distribution.
● Implemented in Python, Golang, C and Bash

Centralized logging for a multi data center distributed system
● Eased debugging and log analysis by implementing centralized logging using rsyslog on ubuntu servers, along
with logrotate policies for archiving historical logs.
● Implemented in Java (logback framework), Python and Bash.



        
        <tr>
          <td><b>Docker Volume Plugin for AWS EFS</b></td>
        </tr>
        <tr>
          <td>Designed and implemented a customized docker volume plugin using the plugin support in docker for persisting container data across a cluster, which ensures that if an application dies/quits and is rescheduled elsewhere in the cluster, a containerized service can restore state before proceeding further.
          </td>
        </tr>
        <tr>
          <td>AWS EFS backend can be swapped out and replaced with other storage technologies, if needed.</td>
        </tr>
        <tr>
          <td>Implemented in golang.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Cluster Management for Big Data Pipeline</b></td>
        </tr>
        <tr>
          <td>Architected & implemented an auto-scaling, cluster management solution from scratch, helping engineers
focus on business logic rather than scale issues, with monitoring giving insight into entire cluster state.</td>
        </tr>
        <tr>
          <td>Tech stack: coreOS, ubuntu, etcd, flannel, docker, apache mesos, apache aurora, bosun, cadvisor, haproxy,
confd, apache kafka, apache cassandra, apache storm, apache spark, AWS EC2.</td>
        </tr>
        <tr>
          <td>Implemented in golang, bash, python.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Stream Analytics</b></td>
        </tr>
          <td>Configured apache kafka to decouple producers and consumers of data for easier service management, fault-tolerance, real-time data processing, and signaling between various microservices.</td>
        <tr>
          <td>Leveraged apache storm for immediate processing and dispatch of data to appropriate consumer services, and to parallelize multiple mutually exclusive operations, optimizing the data processing pipeline.</td>
        </tr>
        <tr>
          <td>Implemented kafka producers and consumers in java, scala and golang.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Batch Analytics</b></td>
        </tr>
        <tr>
          <td>Executed batch analytics jobs using apache spark with apache mesos to perform hourly trend analysis on dataset stored in apache cassandra, to gain insight about network characteristics between various endpoints over different types of links.</td>
        </tr>
        <tr>
          <td>Implemented in scala, python and golang</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Secure Tunnel Overlay Network</b></td>
        </tr>
        <tr>
          <td>Developed a secure network connectivity between various sub-systems/micro-services using openvpn, along with an API-driven certificate authority service for dynamic certificate request authentication, generation and distribution.</td>
        </tr>
        <tr>
          <td>Implemented in python, golang, c and bash.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Centralized logging for a multi data center distributed system</b></td>
        </tr>
        <tr>
          <td>Eased debugging and log analysis by implementing centralized logging using rsyslog on ubuntu servers, along with logrotate policies for archiving historical logs.</td>
        </tr>
        <tr>
          <td>Implemented in bash, java (logback framework), python.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
     <table>
       <tr>
       <td><b>Custom software upgrade workflow</b></td>
       </tr>
       <tr>
         <td>Designed and implemented an update mechanism to check for and download new software packages on low-speed, high-latency network connection, with features like download resumption from point of failure, rollback, caching, and retry mechanisms.</td>
       </tr>
       <tr>
         <td>Implemented in python.</td>
       </tr>
     </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Opendaylight modules</b></td>
        </tr>
        <tr>
          <td>Implemented discovery module, kafka module, and a custom messaging module for the opendaylight SDN controller, which is built as per OSGi specification.</td>
        </tr>
        <tr>
          <td>Implemented in java.</td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>Software Engineer</td>
    <td> Cisco Systems</td>
    <td> July 2012 – April 2014</td>  
  </tr>
  <tr>
    <td colspan="3">
      <table>
       <tr>
       <td><b>Opendaylight SDN Controller</b></td>
       </tr>
       <tr>
         <td>Showcased a proof of concept service chaining of various Cisco services using opendaylight and openflow switches. This was the early proof of concept to showcase Cisco services in the SDN realm.</td>
       </tr>
       <tr>
         <td>Implemented in java and python.</td>
       </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
       <tr>
       <td><b>Protocol Pack Program</b></td>
       </tr>
       <tr>
         <td>Participated in bug resolution, automation and testing of protocol packs, which are a bundle of application protocol signatures to classify various network flows going through a router.</td>
       </tr>
       <tr>
         <td>Implemented in perl, python and C.</td>
       </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td>Software Engineer, Intern</td>
    <td>Cisco Systems</td>
    <td>Jan 2012 – Jun 2012</td>
  </tr>
  <tr>
    <td colspan="3">
      <table>
        <tr>
        <td><b>Network Based Application Recognition Signature Analysis Tool Proof of Concept</b></td>
        </tr>
        <tr>
          <td>Part of a team that developed the for NBAR Signature Analysis Tool, which provides a web interface for rapid prototyping of a custom application signature, and testing it immediately on a set of packet capture files.</td>
        </tr>
        <tr>
          <td>Demonstrated at CiscoLive, 2013.</td>
        </tr>
        <tr>
          <td>Implemented in perl, python and bash.</td>
        </tr>
      </table>
    </td>
  </tr>  
</table>


## Education
<table>
  <tr>
    <td>M.C.A</td>
    <td>VJTI, Mumbai</td>
    <td>July 2009 – June 2012</td>
  </tr>
  <tr>
    <td colspan="3">Master of Computer Applications from Veermata Jijabai Technological Institute, Mumbai. CPI: 9.0/10.</td>
  </tr>
</table>


## Projects
<table>
  <tr>
  <td><b>OS Scheduler Simulator (2010)</b></td>
  </tr>
  <tr>
    <td>Implemented FCFS, SJF, SRTF, Priority, Round Robin algorithms, their variants, simulated the paging process & calculated statistics like throughput, wait time, etc. at program termination.</td>
  </tr>
  <tr>
    <td>Implemented in C.</td>
  </tr>
</table>


## Recognition & Awards
* Mentoring: Mentored interns at Cisco Systems, and led a team of 3 Software Engineers at Ionos Networks on 2 different projects.
* Scholarship: Awarded the Sir Ratan Tata Scholarship under the Studies in India Programme, 2010 – 2011.
* Academic Excellence: Ranked 12th in the University of Mumbai & 20th in the state of Maharashtra at the MAH-MCA-CET 2009 examination with a score of 98.92 percentile.
* Recognition: 3 ‘<u>Cisco Achievement Program<u>’ Awards for outstanding work within a span of 12 months.
