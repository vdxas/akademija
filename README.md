
## About 

<p>
<a href="http://sandbox.nextin.lt:8082">Sklydžiai</a>
</p>

Oro uostai importuojami iš airports1.csv as-is, pridedant id stulpelį 
sql> alter table airports add column `id` int(10) unsigned primary KEY AUTO_INCREMENT;

Šiek tiek logikos:
Įvedant naują skydį, laiko zona yra parenkama automatiškai pagal orouostą, tam kad išvengti žmogiškos klaidos.
Atrodo, kad tai turėtų būti naudinga.
