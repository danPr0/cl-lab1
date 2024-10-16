# Імітація діалогу на українській мові за допомогою системи Eliza

## 1. Загальний огляд системи
Програма шукає у тексті ключові слова, сортує їх за пріорітетом, 
знаходить підходящий паттерн та генерує одну з заданих шаблоном відповідей.

## 2. Адаптація під українську мову
Були створено 2 словники з іменниками та прикметниками. В них вказувється
рід, число, відмінок та словоформа. У паттерні пошуку вони позначаються спеціальними
ключами $noun і $adj, та можуть бути адаптовані під різні форми у відповідях.

## 3. Приклад роботи
'>' _я дуже хочу смачної кави_<br>
Чому ви бажаєте смачну каву ?<br>
'>' _я дуже хочу смачної кави_<br>
Ви робите щось для досягнення смачної кави ?<br>

'>' _я дуже люблю смачну каву_<br>
Що для вас означає любов зі смачною кавою ?<br>
'>' _я дуже люблю смачну каву_<br>
Як ви висловлюєте свою любов до смачної кави ?<br>
