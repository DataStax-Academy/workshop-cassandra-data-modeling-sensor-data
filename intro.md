<!-- TOP -->
<div class="top">
  <img class="scenario-academy-logo" src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-2023.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Sensor Data Modeling</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:aleksandr.volochnev@datastax.com">email</a> or <a href="https://dtsx.io/aleks">LinkedIn</a>.</span>
  </div>
</div>

<!-- CONTENT -->
<main>
    <br/>
    <div class="container px-4 py-2">
     <div class="row g-4 py-2 row-cols-1 row-cols-lg-1">
      <div class="feature col div-choice">
            <div class="scenario-description">Explore how IoT sensor data can be stored and queried in Cassandra NoSQL database.</div>
            <ul>
              <li><span class="scenario-description-attribute">Difficulty</span>: Beginner</li>
              <li><span class="scenario-description-attribute">Time</span>: 15 minutes</li>
              <li><span class="scenario-description-attribute">Prerequisite</span>: <a href="https://www.datastax.com/learn/data-modeling-by-example/sensor-data-model" target="_blank">how to create a data model for temperature monitoring sensor networks</a></li>
            </ul>
            <div class="scenario-objectives">In this hands-on lab, you will:</div>
            <ul>
              <li><span class="scenario-objective">Create tables for a sensor data use case</span></li>
              <li><span class="scenario-objective">Populate tables with sample sensor data</span></li>
              <li><span class="scenario-objective">Design and execute CQL queries over sensor data</span></li>
            </ul>
      </div>
     </div>
    </div>
    <div class="container px-4 py-2">
        <div class="scenario-choices">Run this hands-on lab using Astra DB or Apache Cassandra®:</div><br/>
        <div class="row g-4 py-2 row-cols-1 row-cols-lg-1">
          <div class="feature col div-choice">
            <div class="logo-astradb">
              <img src="https://datastax-academy.github.io/katapod-shared-assets/images/logo-astradb.svg" height="40px" />
            </div>
            <div class="astradb-line1">Cloud database service built on Apache Cassandra</div>
            <div class="astradb-line2">You will connect to a free cloud database service that runs a Cassandra cluster for you.</div>
            <br/>
            <a href='command:katapod.loadPage?[{"step":"step1-astra"}]' class="btn btn-primary btn-astra">
              Start with Astra DB
            </a>
          </div>
          <div class="feature col div-choice">
            <div class="logo-cassandra">
                <img src="https://datastax-academy.github.io/katapod-shared-assets/images/logo-cassandra.png" height="40px" />
            </div>
            <div class="cassandra-line1">Local deployment of open-source Apache Cassandra</div>
            <div class="cassandra-line2">You will use a Cassandra cluster deployed locally in Gitpod using Docker.</div>
            <br/>
            <a href='command:katapod.loadPage?[{"step":"step1-cassandra"}]' class="btn btn-primary btn-cassandra">
              Start with Cassandra
            </a>   
          </div>
        </div>
    </div>
</main>
