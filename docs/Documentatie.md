---
layout: page-with-side-nav
title: Documentatie StUF-ZKN
folder_files:
  - title: GEMMA Referentiezaaktypecatalogus (zip)
    path: documenten/GEMMA_Referentiezaaktypecatalogus_20141231.zip
    group: 2
    versie: 
    status: In bewerking
    omschrijving: 
    datum: 20141231
  - title: GEMMA ZTC 2 - Begeleidend Document (pdf)
    path: documenten/GEMMA_ZTC2_-_Begeleidend_document_v2.1.pdf
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 20140701
  - title: GEMMA ZTC2 - Begeleidend document v2.1 - met wijzigingen tov 2.0 (pdf)
    path: documenten/GEMMA_ZTC2_-_Begeleidend_document_v2.1_-_met_wijzigingen_tov_2.0.pdf
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 20140701
  - title: GEMMA ZTC2 - Zaaktypesjabloon en Toelichting v2.1 (zip)
    path: documenten/GEMMA_ZTC2_-_Zaaktypesjabloon_en_Toelichting_v2.1_2.zip
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
    datum: 20160707
  - title: Voorbeeldzaaktypencatalogus OD haaglanden (pdf)
    path: documenten/OD_Haaglanden_-_Zaaktypecatalogus_v1.0_-_20120210.pdf
    group: 2
    versie: 1.0
    status: In bewerking
    omschrijving: 
    datum: 20120210
  - title: Voorbeeldzaaktypecatalogus ZTC2 (zip)
    path: documenten/ZTC2_-_Voorbeeldzaaktypen.zip
    group: 2
    versie: 1.0
    status: Definitief
    omschrijving: 
    datum: 20150109
---

# Documentatie

## GEMMA ZTC2

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 2 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

