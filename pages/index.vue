<template>
  <v-row>
    <v-col cols="12" sm="12">
      <v-parallax src="/pexels-kevin-ku-577585.jpg">
        <v-row
          align="center"
          justify="center"
        >
          <v-col class="text-center" cols="12">
            <v-avatar height="200" width="200">
              <v-img src="/0.jpeg"/>
            </v-avatar>
            <h1 class="display-2 mb-4">Justin Howard</h1>
            <h4 class="subheading">Senior Software Engineer</h4>
          </v-col>
        </v-row>
      </v-parallax>
    </v-col>
    <v-col cols="12" sm="12">
      <v-card>
        <v-card-title class="display-2 justify-center">About me</v-card-title>
        <v-card-text>
          <v-row>
            <v-col cols="12" sm="12">
              <div class="text-center" style="width: 100%">
                <h4 class="title">I am a full stack senior software engineer. I build things using a variety of
                  tools, but in particular, C# .net core, Vue, TypeScript and MongoDB.</h4>
                <h4 class="title">I used to be an Agile Test and Business Assurance manager so have lots of experience in testing and test driven development.</h4>
              </div>
            </v-col>
            <v-col cols="12" sm="12" md="9">
              <h5 class="display-1">Experience</h5>
              <v-timeline>
                <v-timeline-item left color="green" small>
                  <template v-slot:opposite>
                    <span
                      class="`headline font-weight-bold`"
                      v-text="'Oct 2017 - Present'"
                    ></span>
                  </template>
                  <div class="py-4">
                    <h2 class="`headline font-weight-light mb-4`">Citi</h2>
                    <h5 class="`title font-weight-light mb-4`">Contract Senior Software Engineer</h5>
                    <div>
                      Initially rebuilt Citi Marketplace into a brand new Angular 7+ application. CMP is an internal application is used by approximately 300k staff globally.
                      Now part of the Enterprise workflow team, developing a jBPMN application, in particular a UI to allow users to design workflows and publish them into the workflow engine.
                      <p>Technologies used include:</p>
                      <ul>
                        <li>iOS SDK</li>
                        <li>Node.js</li>
                        <li>Vue.js</li>
                        <li>jBPMN</li>
                        <li>Oracle</li>
                      </ul>

                      <p>Languages:</p>
                      <ul>
                        <li>JavaScript</li>
                        <li>Swift</li>
                        <li>TypeScript</li>
                      </ul>
                    </div>
                  </div>
                </v-timeline-item>
                <v-timeline-item left color="green" small>
                  <template v-slot:opposite>
                    <span
                      class="`headline font-weight-bold`"
                      v-text="'Jul 2016 - Oct 2017'"
                    ></span>
                  </template>
                  <div class="py-4">
                    <h2 class="`headline font-weight-light mb-4`">Sparta Global</h2>
                    <h5 class="`title font-weight-light mb-4`">Lead Development Consultant</h5>
                    <div>
                      From July 2016 to January 2017, trained Web Dev, Test, and SDET trainees in HTML, CSS, Javascript, Agile, and business skills. January 2017 to October 2017 on site at Canada Life as a Lead Development Consultant.

                      <ul>
                        <li>Creating and driving Dev Ops strategy across IS and engagement with ETS</li>
                        <li>Introducing TDD and BDD testing frameworks across IS development teams to improve quality through continuous integration in line with Agile transformation strategy</li>
                        <li>Facilitating and advising on the implementation of coding standards across IS development teams alongside IS senior developers</li>
                        <li>Lead developer on projects that have been identified as needing remediation or improvement, including managing source code repositories and deployments</li>
                        <li>Managing Sparta developers on site with programming enquiries, across multiple projects including bulk annuities, prophet, and remediation work</li>
                        <li>Providing onsite training to existing developers in web technologies such as HTML, CSS, REST, and Single Page Applications</li>
                      </ul>

                      <div>
                        <p>Technologies used</p>
                        <ul>
                          <li>ASP .Net Core</li>
                          <li>Vue.JS</li>
                          <li>Angular 2</li>
                          <li>SQL Server 2014</li>
                          <li>Windows Server 2012</li>
                          <li>IIS</li>
                      </ul>
                      </div>
                    </div>
                  </div>
                </v-timeline-item>
                <v-timeline-item left color="green" small>
                  <template v-slot:opposite>
                    <span
                      class="`headline font-weight-bold`"
                      v-text="'Sep 2015 - Jun 2016'"
                    ></span>
                  </template>
                  <div class="py-4">
                    <h2 class="`headline font-weight-light mb-4`">Citi</h2>
                    <h5 class="`title font-weight-light mb-4`">Contract Software Developer</h5>
                    <div>
                      Building internal Enterprise Applications for Citigroup using both Cross Platform and Native frameworks

                      Applications run on both iOS and Android using the Appcelerator Titanium cross platform framework, which is powered by Javascript.

                      <p>Technologies used include:</p>
                      <ul>
                        <li>iOS SDK</li>
                        <li>Android SDK</li>
                        <li>Appcelerator Platform</li>
                        <li>Arrow</li>
                        <li>Alloy MVC</li>
                        <li>Appcelerator Titanium</li>
                        <li>Node.js</li>
                        <li>SVN</li>
                        <li>Microstrategy</li>
                        <li>Good Dynamics</li>
                      </ul>

                      <p>Languages:</p>
                      <ul>
                        <li>JavaScript</li>
                        <li>Swift</li>
                      </ul>
                    </div>
                  </div>
                </v-timeline-item>
                <v-timeline-item left color="green" small>
                  <template v-slot:opposite>
                    <span
                      class="`headline font-weight-bold`"
                      v-text="'Dec 2013 - Sep 2015'"
                    ></span>
                  </template>
                  <div class="py-4">
                    <h2 class="`headline font-weight-light mb-4`">Lexel</h2>
                    <h5 class="`title font-weight-light mb-4`">Consultant Developer and Technical Advisor</h5>
                    <div>
                      Providing technical advice on all things Node.js and Mongo.

                      Meeting with Clients to define their business requirements, generating a technical approach and architecture, followed by engineering and testing the solution.

                      Technology used:
                      Appcelerator Titanium
                      Node.js
                      Express
                      Angular.js
                      MongoDB
                      Heroku
                      Semaphore CI
                      Javascript
                      HTML 5
                      CSS3
                      Bootstrap
                      JQuery
                    </div>
                  </div>
                </v-timeline-item>
              </v-timeline>
            </v-col>
            <v-col cols="12" sm="12" md="3">
              <h5 class="display-1">Skills</h5>
              <div class="title mt-3">
                JavaScript, <span class="blue--text darken-3">TypeScript</span>, Vue.js, <span class="blue--text darken-3">Node.js</span>, Angular, <span class="blue--text darken-3">MongoDB</span>, C#, <span class="blue--text darken-3">.net core</span>,
                Docker, <span class="blue--text darken-3">Kubernetes</span>, Swift, <span class="blue--text darken-3">HTML 5</span>, CSS 3, <span class="blue--text darken-3">SASS</span>
              </div>
              <v-card color="blue darken-3 mt-5">
                <v-card-title class="justify-center white--text">Contact me</v-card-title>
                <v-card-text class="text-center">
                  <p class="white--text title">Do you like my CV?
                    Feel free to contact me</p>
                </v-card-text>
                <v-card-actions>
                  <v-btn @click="email" color="white" block>Contact Me</v-btn>
                </v-card-actions>
              </v-card>
            </v-col>
            <v-col cols="12" sm="12">
              <v-card color="blue darken-3">
                <v-card-text>
                  <v-row>
                    <v-col class="text-center">
                      <v-btn @click="goToLink('github')" x-large color="white" icon><v-icon>mdi-github</v-icon></v-btn>
                    </v-col>
                    <v-col class="text-center">
                      <v-btn @click="goToLink('linkedin')" x-large color="white" icon><v-icon>mdi-linkedin</v-icon></v-btn>
                    </v-col>
                    <v-col class="text-center">
                      <v-btn @click="goToLink('instagram')" x-large color="white" icon><v-icon>mdi-instagram</v-icon></v-btn>
                    </v-col>
                  </v-row>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>

export default {
  methods: {
    email() {
      window.open('mailto:justin@justinhoward.co.uk?&subject=Web Query', '_self')
    },
    goToLink(link) {
      if (link === 'github') {
        window.open('https://github.com/justin-nodeboy', '_blank')
      }
      if (link === 'linkedin') {
        window.open('https://www.linkedin.com/in/nodejustin/', '_blank')
      }
      if (link === 'instagram') {
        window.open('https://www.instagram.com/nodejustin/', '_blank')
      }
    }
  }
}
</script>
