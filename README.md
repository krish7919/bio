## Summary
* 4+ years in software engineering, with 2+ years in analyzing, designing, implementing, troubleshooting, and operating a big data pipeline, as a cross-data center distributed system using microservices. Possess in-depth knowledge of backend architecture required for modern web-scale applications.
* Self-motivated, strong communication and collaboration skills, and work with minimal supervision.
* Repeatedly recognized as fast learner and executor, meeting critical deadlines by managing technical debt effectively.
* Practitioner of agile methodology and test driven development.
* Well-informed with emerging and disruptive technologies, leveraging them to improve current systems.
<table>
  <tr>
    <td colspan="2">Technologies</td>
  </tr>
  <tr>
    <td colspan="2"><b>Cluster management</b>: &nbsp;&nbsp;&nbsp;Mesos, Aurora, Zookeeper, Docker, Bosun, cAdvisor</td>
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
    <td><b>Public Cloud Platforms</b>: AWS EC2, GCE</td>
    <td><b>Tools</b>: Eclipse, Git, Maven</td>
  </tr>
</table>


## Employment History
<table>
  <tr>
    <td>Member of Technical Staff</td>
    <td>Ionos Networks/IP Core Solutions</td>
    <td>May 2014 - Nov 2016</td>  
  </tr>
  <tr>
    <td colspan="3">
      <table>
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
