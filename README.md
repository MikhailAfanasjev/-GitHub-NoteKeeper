NoteKeeper - это простое приложение для Android, которое позволяет пользователям создавать, просматривать и удалять заметки. Приложение построено на основе Room, что обеспечивает удобное управление базой данных, а также использует RecyclerView для отображения списка заметок.

Основные функции
Создание заметок: Пользователи могут добавлять новые заметки с заголовком и описанием.
Просмотр заметок: Заметки отображаются в виде списка. При нажатии на заметку отображаются её подробности.
Удаление заметок: Заметки можно удалять смахиванием влево.
Управление базой данных: Все данные сохраняются локально с использованием Room.
Технологии
Room: Для работы с базой данных SQLite.
RecyclerView: Для отображения списка заметок.
ExecutorService: Для выполнения операций с базой данных в фоновом потоке.
