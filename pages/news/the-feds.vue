<template>
  <div>
     <base-bg-top
      :name="`The Feds, Police Are Using Google's Location History Feature to Track Down Suspects`"
      :date="'2019-04-08'"
    ></base-bg-top>
    
      <v-container>
        <p>
          Law enforcement queries of Google’s massive mobile device Location History database,
          which employees call Sensorvault, has “risen sharply in the past six months,”
          the
          <a
            class="a"
            href="https://www.nytimes.com/interactive/2019/04/13/us/google-location-tracking-police.html"
          >New York Times reported</a> on Saturday, citing sources at the company.
        </p>
        <p>
          It’s not clear how often police ask Google to produce results from the database,
          which can be used to narrow down which devices were in a specified geographic location at a
          certain period of time (mostly phones running its Android OS, but also some ones on Apple’s iOS).
          The technique can be used to generate leads.
          But critics say it resembles a fishing expedition that raises constitutional questions under the Fourth Amendment,
          which restricts the scope of warrants and mandates authorities show probable cause to search, the Times wrote:
        </p>
        <p>
          The practice was first used by federal agents in 2016,
          according to Google employees, and first publicly reported last year in
          <a
            class="a"
            href="https://www.wral.com/Raleigh-police-search-google-location-history/17377435/"
          >North Carolina</a>.
          It has since spread to local departments across the country, including in California,
          <a
            class="a"
            href="https://int.nyt.com/data/documenthelper/764-fdlelocationsearch/d448fe5dbad9f5720cd3/optimized/full.pdf#page=1"
          >Florida</a>,
          <a
            class="a"
            href="https://www.mprnews.org/story/2019/02/07/google-location-police-search-warrants"
          >Minnesota</a> and Washington. This year, one Google employee said, the company received as many as 180 requests in one week.
          Google declined to confirm precise numbers.
        </p>
        <p>
          The technique illustrates a phenomenon privacy advocates have long referred to as the “if you build it,
          they will come” principle — anytime a technology company creates a system that could be used in surveillance,
          law enforcement inevitably comes knocking. Sensorvault, according to Google employees,
          includes detailed location records involving at least hundreds of millions of devices worldwide and dating back
          nearly a decade.
        </p>
        <p>
          Last year, the
          <a
            class="a"
            href="https://www.nytimes.com/2018/06/22/us/politics/supreme-court-warrants-cell-phone-privacy.html"
          >U.S. Supreme Court ruled</a> that authorities must obtain a search warrant and show
          probable cause to obtain location records from third parties like Google, though Google had already
          decided that it would demand warrants to hand over the data. Since each “geofence warrant”—varying from
          tiny spaces to larger areas covering multiple blocks, and over similarly variable periods of time—can potentially
          rope in tens to hundreds of devices owned by many people, the company first provides records without attaching names
          or other identifying information to investigators.
        </p>
        <p>
          Once authorities narrow down the number of leads, such as by identifying patterns of movement that
          indicate potential involvement in a crime or potential witnesses that were in the area, they can request
          further location data or ask Google to reveal “the name, email address and other data associated with the device,”
          the Times wrote. However, some jurisdictions can require a second warrant before identifying information is handed over.
        </p>
        <p>
          As the Times
          <a
            class="a"
            href="https://www.nytimes.com/2019/04/13/technology/google-sensorvault-location-tracking.html"
          >separately reported</a>, Location History is not enabled by default and has to be
          activated when opting in to certain services. Its primary purpose for Google, however,
          is targeted advertising and services like determining when stores are busy. Even if Location History is
          turned off, other Google apps collect some location data as part of Web & App Activity settings
          (though this data is kept in a
          <a
            class="a"
            href="https://apnews.com/828aefab64d4411bac257a07c1af0ecb"
          >separate Google database</a>).
        </p>
        <p>
          While the warrants have solved crimes, they can also result in authorities nabbing the wrong person.
          For example, the Times explained the case of Phoenix man Jorge Molina, who was arrested after police
          said his phone was detected in the vicinity of a drive-by shooting and then realized his vehicle resembled
          one at the crime scene picked up by security video. Molina spent a week in jail before friends produced texts
          and Uber receipts backing up an alibi, while police later arrested Marcos Gaeta, “his mother’s ex-boyfriend,
          who had sometimes used Mr. Molina’s car” and had a “lengthy criminal record.”
        </p>
        <p>
          Molina’s public defender, Jack Litwak, told the paper he believed it was possible that Google’s
          records were misleading due to multiple sign-ins:
        </p>
        <p>
          Litwak said his investigation found that Mr. Molina had sometimes signed in to other people’s phones to check his
          Google account. That could lead someone to appear in two places at once, though it was not clear whether that
          happened in this case.
        </p>
        <p>
          According to the Times, Google is the primary company that appears to be fulfilling the warrants
          (Apple says it can’t provide this information to authorities).
          However, last year another company called Securus was
          <a
            class="a"
            href="https://gizmodo.com/a-shady-company-offering-police-cellphone-location-data-1826081159"
          >reported to have obtained</a> location data directly
          from telecoms that it then sold to law enforcement without a warrant. A
          <a
            class="a"
            href="https://gizmodo.com/black-market-for-your-location-data-apparently-thriving-1831584165"
          >thriving black market</a> in location data
          has persisted despite promises from carriers to stop selling it to middlemen, who divert it from intended uses in
          marketing and other services.
        </p>
      </v-container>
    
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>OTHER NEWS</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
        <base-new-text></base-new-text>
        <!-- <v-row>
          <v-container>
            <v-col cols="12">
              <v-hover v-slot="{ hover }">
                <v-card to="/new/vietnam" :elevation="hover ? 12 : 2">
                  <base-tech-new
                    img="/anhtech1.jpg"
                    :title="'Việt Nam có thể trở thành cường quốc an ninh mạng'"
                    :date="'2019-4-17'"
                  ></base-tech-new>
                </v-card>
              </v-hover>
            </v-col>
            <v-col cols="12">
              <v-hover v-slot="{ hover }">
                <v-card to="/new/thefeds" :elevation="hover ? 12 : 2">
                  <base-tech-new
                    img="/anhtech2.jpg"
                    :title="'The Feds, Police Are Using Google is Location History Feature to Track Down Suspects'"
                    :date="'2019-4-8'"
                  ></base-tech-new>
                </v-card>
              </v-hover>
            </v-col>
            <v-col cols="12">
              <v-hover v-slot="{ hover }">
                <v-card to="/new/damn" :elevation="hover ? 12 : 2">
                  <base-tech-new
                    img="/anhtech3.jpg"
                    :title="'Damn, Could the Samsung Galaxy Fold Be Worth It?'"
                    :date="'2019-4-8'"
                  ></base-tech-new>
                </v-card>
              </v-hover>
            </v-col>
          </v-container>
        </v-row> -->
      </v-container>
    </v-row>
  </div>
</template>

<style lang="scss">
.a {
  text-decoration: none;
}
</style>