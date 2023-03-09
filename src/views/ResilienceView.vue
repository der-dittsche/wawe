<template>
  <main>
    <h1>Resilienz</h1>
    <p>
      Unser Schwerpunkt im Jahr 2022 lautete: “Dem Klimawandel gemeinsam und konstruktiv begegnen –
      Resiliente Lebensstile entwickeln und auf Klimafolgen reagieren.”
    </p>
    <p>
      Um das Thema inhaltlich zugänglich zu machen haben wir hier nach und nach einige Informationen
      und Quellen nach Schwerpunkten sortiert aufgelistet.
    </p>

    <div class="resilience__box diagonal">
      <article class="resilience__box-article wrapper">
        <h2 class="resilience__box-title" @click="this.resilience1 = !this.resilience1">
          Resiliente Landwirtschaft
        </h2>
        <div class="resilience__box-content" v-if="resilience1">
          <p class="resilience__box-header">
            Klimafolgenanpassung in der Landwirtschaft und im Garten – Versorgung im Wandel
          </p>
          <p>
            Der Klimawandel ist da. Hitze, Stürme, Dürren, Starkregenereignisse und Überschwemmungen
            sind auch in unseren Breiten angekommen. Ernteausfälle und ausgedörrte oder auch
            weggeschwemmte Böden lassen teilweise Agrarwüsten entstehen. Unsere Abhängigkeit von
            außen wird sichtbar durch die Versorgungsengpässe in der Pandemie, dadurch verschärft
            sich die Situation zusätzlich. Es ist in diesen Zeiten so relevant wie nie zuvor, unsere
            Anbausysteme zu überdenken und unabhängig zu machen von Extremwetterereignissen und
            globalen Krisen. Resilienz können wir noch steigern, wenn wir uns im Kleinen auch wieder
            befähigen, Nahrungsmittel selbst zu produzieren, im eigenen Garten oder auf dem Balkon,
            allein oder zusammen mit anderen, beispielsweise in Gemeinschaftsgärten oder
            solidarischen Landwirtschaften (SoLaWis).
          </p>
          <p>
            Verschiedene Fragen beschäftigen uns, z.B wie können wir Landnutzung aufbauend statt
            ausbeuterisch gestalten? Wie können wir im Großen und im Kleinen unabhängiger werden?
            Wir wollen neue Wege vorstellen, die in Einklang mit der Natur, unserer Lebensgrundlage
            Boden aber auch mit unserem Fortschritt arbeiten und Ideen für die
            Nahrungsmittelversorgung der Zukunft zusammenstellen. Hierfür stellen wir im Folgenden
            verschiedene Themenbereiche vor:
          </p>
          <ul>
            <li>
              Permakultur – die ganzheitliche Sichtweise. Für ein befreundetes Permakulturprojekt in
              Kenia kannst du beispielsweise hier spenden.
            </li>
            <li>
              Agroforstwirtschaft – die eierlegende Wollmilchsau. Wie wäre es, wenn Wind und Hitze
              dem Acker nichts mehr anhaben könnte, er sich selbst düngt, man die Ernte dabei
              verdoppelt, die Biodiversität und die Nitratauswaschung stoppt und nebenbei noch
              Energieholz produziert? Zum Thema Agroforstwirtschaft empfehlen wir die Arte-Doku “Mit
              Bäumen gegen die Dürre“
            </li>
            <li>
              Regenerative Landwirtschaft und Humusaufbau – Klimafolgenanpassung durch
              Humusmanagement. Dazu empfehlen wir die Arte-Doku “Mit lebendiger Erde das Klima
              retten” und die Doku-Reihe “Roots”.
            </li>
            <li>
              Essbare Stadt + urban gardening – gärtnern geht überall! Wir haben einen kleinen,
              urbanen Stadtgarten hinter der Wandel-Werkstatt gestartet!
            </li>
            <li>
              Biodiversität als Antwort auf das Artensterben – Ende Mai 2022 veranstalteten wir
              einen Familien-Mitmachtag in Schlangen zu dem Thema. Einen Bericht samt
              weiterführenden Informationen dazu könnt ihr hier lesen. Eine schöne Übersicht zum
              Thema insektenfreundliche Gärten und Balkone gibt es außerdem hier.
            </li>
            <li>
              Essbarer Wildpflanzenpark – die neue Allmende – komm und nimm dir was du brauchst!
              Informationen zum Essbaren Wildpflanzenpark in Bad Lippspringe an dessen Aufbau wir
              mitgewirkt haben gibt es hier.
            </li>
            <li>
              Solidarische Landwirtschaft – gemeinsam ackern und die Ernte teilen. Schaut mal vorbei
              bei den lippischen Solawis: In Blomberg-Dalborn, in Schlangen, in Kalletal und in
              Lage.
            </li>
            <li>Waldgarten – gärtnern im Wald?</li>
            <li>
              Stadtbäume und Streuobstwiesen – oder beides? Wie wäre es, wenn man im Park nicht nur
              chillen sondern auch essen könnte? Was können sie leisten? Biodiversität, Kühlung,
              Nahrung, Stadtklima günstig für Südbäume, Parks als Wohnzimmer der Straße. Auf der
              Online-Karte Mundraub.org kann man Fundorte mit Obstbäumen, Obststräuchern, Nüssen und
              Kräutern finden oder diese selbst kartieren.
            </li>
            <li>
              Selbstversorgung von Balkon und Beet – Ein Einstieg (No-Dig-Methode, Hochbeete,
              Pflanzenportraits für den Einstieg)
            </li>
          </ul>
          <p>Aktuelle Veranstaltungen von uns findest du hier.</p>
        </div>
      </article>
    </div>

    <div class="resilience__box">
      <article class="resilience__box-article wrapper">
        <h2 class="resilience__box-title" @click="this.resilience2 = !this.resilience2">
          Resiliente Energieversorgung
        </h2>
        <div class="resilience__box-content" v-if="resilience2">
          <p>
            Ob Stoppen der Erderhitzung oder Unabhängigwerden von Diktatoren: Wind- und Solarkraft
            sind die besten Wege, um die Energiewende dezentral voran zu bringen und resilient zu
            werden. Wir möchten hier ein paar Links mit euch teilen zu Möglichkeiten, wie daran
            mitgearbeitet werden kann.
          </p>
          <ul>
            <li>
              Die Verbraucherzentrale NRW stellt zahlreiche Informationen über individuelle
              Möglichkeiten für Solarenergie zur Verfügung. Dazu zählen zum Beispiel auch
              Balkonkraftwerke.
            </li>
            <li>
              Viele Informationen zu Veranstaltungen zur Energiewende in OWL findet man übrigens im
              Forum Erneuerbare Energien – Ost Westfalen Lippe
            </li>
            <li>
              Bei Facebook gibt es zudem die Gruppe “Europäische Energiewende” in der zahlreiche
              Lösungen und Tipps diskutiert werden.
            </li>
          </ul>
          <p>
            An die Folgen der Klimakrise anpassen können wir uns jedoch nur, wenn die Erdsysteme
            stabilisiert werden. Dazu ist eine schnelle Energiewende nötig. Nur noch wenige Jahre
            bleiben dafür, wie ein Blick auf die “Climate Clock” zeigt:
          </p>
        </div>
      </article>
    </div>

    <div class="resilience__box diagonal">
      <article class="resilience__box-article wrapper">
        <h2 class="resilience__box-title" @click="this.resilience3 = !this.resilience3">
          Resiliente Gemeinschaften
        </h2>
        <div class="resilience__box-content" v-if="resilience3">
          <p>
            Die sich verschärfende ökologische Krise samt Zunahme von Extremwetter, Artensterben und
            deren Folgen erfordert konstruktives Zusammenarbeiten auf lokaler Ebene. Wir versuchen
            dies in unserem Projekt mit verschiedenen Aktionsgruppen zu leisten.
          </p>
          <ul>
            <li>
              Die Aktionsgruppe Lebenswertes Detmold setzt sich beispielsweise für das Retten von
              Stadtbäumen ein.
            </li>
            <li>
              Im Repair Cafe Detmold können Besucher*innen bei Kaffee und Kuchen gemeinsam
              Gegenstände reparieren.
            </li>
            <li>
              Beim Talentetausch geht es darum sich bei verschiedenen Tätigkeiten zu unterstützen
              indem Talente ausgetauscht werden.
            </li>
            <li>
              Aktionsgruppe “Gemeinschaftsgarten Schlangen”: Alt und Jung, Teilen von Wissen und
              Ernte
            </li>
            <li>
              Foodsharing: Für immer mehr Menschen eine wichtige Gelegenheit, um auf steigende
              Lebensmittelpreise regieren zu können
            </li>
            <li>
              Unser Leitfaden „Gemeinsam vorbereiten“, den wir Ende 2022 fertiggestellt haben hat
              seinen Schwerpunkt auf nachbarschaftliche Zusammenarbeit in Bezug auf Klimafolgen.
              Enthalten sind unter anderem die Methode des Nachbarschaftsmappings, bei der Personen
              gemeinsam eine Karte von ihrer Nachbarschaft erstellen können und Informationen
              austauschen, um im Ernstfall gemeinschaftlich gut auf Klimafolgen reagieren zu können.
            </li>
          </ul>
          <p>Weitere Gruppen sind immer herzlich willkommen! Sprecht uns gerne an.</p>
        </div>
      </article>
    </div>

    <div class="resilience__box">
      <article class="resilience__box-article wrapper">
        <h2 class="resilience__box-title" @click="this.resilience4 = !this.resilience4">
          Leitfaden “Gemeinsam vorbereiten”
        </h2>
        <div class="resilience__box-content" v-if="resilience4">
          <p>
            Im Rahmen unseres Projekts “Dem Klimawandel gemeinsam und konstruktiv begegnen –
            Resiliente Lebensstile entwickeln und auf Klimafolgen reagieren.” haben wir einen
            Leitfaden für Nachbarschaften zum Thema Klimafolgenanpassung erstellt. Zusätzlich zur
            gedruckten Version stellen wir hier eine Online-Version als PDF-Datei zur Verfügung.
          </p>
          <p>
            Des Weiteren stehen hier weitere Arbeitszettel und Dokumente aus dem Leitfaden als
            einzelne Dateien zum Download und Ausdrucken bereit:
          </p>
          <ul>
            <li>Einschätzung der eigenen Vulnerabilität</li>
            <li>Ressourcenliste für Nachbarschaftsmapping</li>
            <li>Kontaktliste für Nachbarschaftsmapping</li>
            <li>Info-Zettel für Nachbarschaftsmapping</li>
            <li>Checkliste Notfallgepäck</li>
          </ul>
          <p>Aktuelle Veranstaltungen von uns findest du hier.</p>
        </div>
      </article>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      resilience1: false,
      resilience2: false,
      resilience3: false,
      resilience4: false
    }
  }
}
</script>

<style>
.resilience__box-header {
  font-weight: 600;
}
.resilience__box-title {
  cursor: pointer;
}
</style>
