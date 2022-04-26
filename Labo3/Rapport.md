# Rapport labo 3 MAC

Question D.1

PUT /cacm_standard
{
  "mappings": {
    "properties": {
      "id":    { "type": "keyword", "index": false},
      "authors":  { "type": "keyword"}, 
      "title":   { "type": "text", "fielddata": true},
      "date": {"type": "date"},
      "summary": {"type": "text", "fielddata": true, "index_options": "offsets"}
    }
  }
}



