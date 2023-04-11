import random
import os
from PIL import Image, ImageDraw, ImageFilter

# Создаем новую папку с именем "nft", если ее еще нет
if not os.path.exists('nft'):
    os.makedirs('nft')

# Список цветов для использования
colors = [
    (255, 255, 255),  # белый
    (0, 0, 0),  # черный
    (255, 0, 0),  # красный
    (0, 255, 0),  # зеленый
    (0, 0, 255),  # синий
    (255, 255, 0),  # желтый
    (255, 0, 255),  # фуксия
    (0, 255, 255)  # голубой
]

# Список символов для использования
symbols = [
    '☀️', '☁️', '⚡', '❄️', '🌊', '🔥', '🌈', '🌙', '🪐', '⭐️', '✨', '💫', '🌟', '🌠'
]

# Список элементов природы для использования
nature_elements = [
    '🌳', '🌴', '🌵', '🌲', '🌷', '🌸', '🍁', '🍃', '🍂', '🍀', '🍄', '🌾', '🌻', '🌺'
]

# Список элементов космоса для использования
space_elements = [
    '🚀', '🛰️', '🪐', '🌠', '🌌', '🌎', '🌕', '🌖', '🌗', '🌘', '🌑', '🌒', '🌓', '🌔'
]

draw = ImageDraw.Draw(image)
# Рисуем случайные символы и элементы на изображении
image = Image.new('RGB', (512, 512), color=(255, 255, 255))
for g in range(25):
    # Выбираем случайный символ или элемент для рисования
    if random.random() < 0.5:
        symbol = random.choice(symbols)
    else:
        if random.random() < 0.5:
            symbol = random.choice(nature_elements)
        else:
            symbol = random.choice(space_elements)

    # Выбираем случайный размер, положение и цвет для символа или элемента
    size = random.randint(20, 60)
    x = random.randint(0, 512 - size)
    y = random.randint(0, 512 - size)
    color = random.choice(colors)

    # Рисуем символ или элемент на изображении
    draw.text((x, y), symbol, fill=color, font=None, stroke_width=0)

# Добавляем размытие к изображению
image = image.filter(ImageFilter.BLUR)

for i in range(2211):
    # Создаем новое изображение
    image = Image.new('RGB', (512, 512), color=random.choice(colors))

    # Создаем функцию для генерации случайной точки на изображении
    def random_point():
        return (random.randint(0, 511), random.randint(0, 511))

    # Начальные точки для алгоритма фрактальной графики
    points = [(0, 0), (0, 511), (511, 511), (511, 0)]

    # Генерируем 1000 новых точек с помощью алгоритма
    for j in range(1000):
        p = random_point()
        index = random.randint(0, 3)
        x, y = points[index]
        points.append(((p[0] + x) // 2, (p[1] + y) // 2))

    # Создаем новый список точек, удаляя первые 4 точки
    points = points[4:]

    # Начинаем рисовать узор на изображении
    draw = ImageDraw.Draw(image)

    for k in range(5000):
        # Выбираем случайную точку из списка
        p = random.choice(points)

        # Выбираем случайный цвет и размер круга
        color = (random.randint(0, 255), random.randint(0, 255), random.randint(0, 255))
        size = random.randint(1, 10)

        # Рисуем круг на выбранной точке
        draw.ellipse((p[0] - size, p[1] - size, p[0] + size, p[1] + size), fill=color, outline='white')

        # Добавляем текстуру круга
        texture_type = random.choice(['dots', 'lines', 'stripes', 'none'])
        if texture_type == 'dots':
            for j in range(size):
                dot_size = random.randint(1, 3)
                dot_color = (random.randint(0, 255), random.randint(0, 255), random.randint(0, 255))
                draw.ellipse((p[0] - j, p[1] - j, p[0] + j, p[1] + j), fill=dot_color, outline=None)
        elif texture_type == 'lines':
            line_width = random.randint(1, 3)
            line_color = (random.randint(0, 255), random.randint(0, 255), random.randint(0, 255))
            draw.line((p[0] - size, p[1], p[0] + size, p[1]), fill=line_color, width=line_width)
            draw.line((p[0], p[1] - size, p[0], p[1] + size), fill=line_color, width=line_width)
        
        # Сохраняем изображение в папке "nft" под именем "nft{i}.png"
    image.save(f'nft/nft{i}.png')
