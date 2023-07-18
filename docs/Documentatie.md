---
layout: page-with-side-nav
title: Documentatie Betalen- en Invorderenservices
folder_files:
  - title: Betalen en invorderen v1.00 - Berichtschemas.zip
    path: documenten/Betalen_en_invorderen_v1.00_-_Berichtschemas.zip
    group: 10
    versie: 
    status: 
    omschrijving: 
  - title: Betalen en invorderen v1.00.01 - Berichtschemas.zip
    path: documenten/Betalen_en_invorderen_v1.00.01_-_Berichtschema_s.zip
    group: 10
    versie: 1.00.01
    status: 
    omschrijving: 
  - title: Betalen en invorderen v1.00.02 - Berichtschemas.zip
    path: documenten/Betalen_en_invorderen_v1.00.02_-_Berichtschema_s.zip
    group: 10
    versie: 1.00.02
    status: Onbekend
    omschrijving: 
  - title: Betalen en invorderen v1.00.03 - Berichtschemas.zip
    path: documenten/Betalen_en_invorderen_v1.00.03_-_Berichtschema_s.zip
    group: 10
    versie: 1.00.03
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Keten Betalen en Invorderen v1.00
    path: documenten/Koppelvlakspecificatie_Keten_Betalen_en_Invorderen_v1.00.pdf
    group: 10
    versie: 1.0
    status: 
    omschrijving: 
  - title: Testset betalen en Invorderen 1.0
    path: documenten/Testset_betalen_en_Invorderen_1.0.zip
    group: 10
    versie: 1.0
    status: Onbekend
    omschrijving: 
---

# Documentatie

## Betalen- en Invorderenservices 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 10 %} 
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
