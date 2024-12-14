# Security By Design - Zadanie 2

## Zadanie 1 -

Weryfikacja wycieku wrażliwych danych

**Cel:** Celem zadania jest przetestowanie aplikacji w celu weryfikacji, czy w logach znajdują się wrażliwe dane, które
niekoniecznie powinny być zawarte w logach aplikacyjnych.

### Znalezione dane wrażliwe:

Analizując logi aplikacji Python, zauważono dane wrażliwe w postaci danych dodawanego klienta.

![ex1_log_not_secure.png](images/ex1_log_not_secure.png)

Zabezpieczono aplikację, anonimizując logi poprzez modyfikację pliku customers/models.py

![ex1_log_secure.png](images/ex1_log_secure.png)