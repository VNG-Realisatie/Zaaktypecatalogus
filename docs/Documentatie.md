---
layout: page-with-side-nav
title: Documentatie StUF-ZKN
folder_files:
  - title: GEMMA Referentiezaaktypecatalogus 
    path: documenten/GEMMA_Referentiezaaktypecatalogus_20141231.zip
    group: 2
    versie: 
    status: In bewerking
    omschrijving: 
  - title: GEMMA ZTC 2 - Begeleidend Document
    path: documenten/GEMMA_ZTC2_-_Begeleidend_document_v2.1.pdf
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
  - title: GEMMA ZTC2 - Begeleidend document v2.1 - met wijzigingen tov 2.0 
    path: documenten/GEMMA_ZTC2_-_Begeleidend_document_v2.1_-_met_wijzigingen_tov_2.0.pdf
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
  - title: GEMMA ZTC2 - Zaaktypesjabloon en Toelichting v2.1 
    path: documenten/GEMMA_ZTC2_-_Zaaktypesjabloon_en_Toelichting_v2.1_2.zip
    group: 2
    versie: 2.1
    status: Definitief
    omschrijving: 
  - title: Voorbeeldzaaktypencatalogus OD haaglanden
    path: documenten/OD_Haaglanden_-_Zaaktypecatalogus_v1.0_-_20120210.pdf
    group: 2
    versie: 1.0
    status: In bewerking
    omschrijving: 
  - title: Voorbeeldzaaktypecatalogus ZTC2
    path: documenten/ZTC2_-_Voorbeeldzaaktypen.zip
    group: 2
    versie: 1.0
    status: Definitief
    omschrijving: 
---

# Documentatie

## GEMMA ZTC2

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
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
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

