ZALEŻNOŚCI
==========

Skrypt używa następujących modułów:

    use Cwd
    use File::Basename
    use File::Copy
    use File::Slurp
    use File::Temp
    use Getopt::Long
    use Try::Tiny
    use YAML

Jeśli brakuje jakiegoś modułu to należy go zainstalować, np poleceniem:

    cpanm MODULE

INSTALACJA
==========

Zainstalować brakujące moduły.

Skopiować skrypt a2pdf do odpowiedniego katalogu bin. Można użyć skryptu
install, który instaluje a2pdf w ~/bin. Katalog docelowy można zmienić
edytując skrypt install ($BINDIR).

Jeśli trzeba zmienić domyślną konfigurację to skopiować plik
conf/a2pdf.conf do ~/.a2pdf.conf i wyedytować go.

DOKUMENTACJA
============

Dokumentacja w postaci POD jest zawarta w skrypcie - można ją wyświetlić
poleceniem:

    perldoc a2pdf
