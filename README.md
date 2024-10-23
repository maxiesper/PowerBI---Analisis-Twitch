# PowerBI---Analisis-Twitch
Analisis de plataforma de stream Twitch de usuarios gamers

Dashboard de Power BI: Análisis de Transmisiones de Videojuegos en Twitch
Este proyecto consiste en un dashboard interactivo desarrollado en Power BI, que analiza las transmisiones en vivo de videojuegos en la plataforma Twitch durante la semana del 7 de noviembre de 2022 al 13 de noviembre de 2022. El análisis incluye una vista detallada de las tendencias de transmisión, con un enfoque especial en el lanzamiento del esperado juego God of War Ragnarök, que ocurrió el miércoles 9 de noviembre a las 5am UTC+0.

Descripción del dataset
El análisis se basa en dos archivos principales:

StreamsInfo: Contiene datos sobre cada videojuego transmitido en Twitch cada 30 minutos, incluyendo el número de canales transmitiendo el juego y el número de espectadores viendo esos canales. La información está en la zona horaria UTC+0 (Londres).
GamesInfo: Incluye detalles específicos de cada videojuego como ID, nombre, clasificación, género, consola, modo de juego, perspectiva del jugador y fecha de lanzamiento.
Objetivo
El objetivo de este dashboard es proporcionar una herramienta visual que permita a los usuarios explorar las tendencias de visualización y transmisión de videojuegos en Twitch, con la capacidad de analizar en detalle la popularidad de diferentes títulos, incluido God of War Ragnarök durante su semana de lanzamiento.

Características principales
Análisis temporal: Visualización de la actividad de transmisión y espectadores a lo largo del tiempo, dividida en intervalos de 30 minutos.
Indicadores clave: Medias de espectadores y streams, junto con la métrica "Espectadores por Stream", que permite estimar cuántos espectadores hay por cada canal de transmisión en un momento dado.
Filtros interactivos: Posibilidad de filtrar por juego, género, consola y más para un análisis más específico.
Impacto del lanzamiento de God of War Ragnarök: Comparación de la actividad antes y después del lanzamiento de este juego.
Terminología clave en el dashboard
Stream: Un canal que transmite contenido en Twitch.
Espectador: Una persona que visualiza un stream específico.
Media de Espectadores y Streams: Promedio concurrente de las capturas de datos en intervalos de 30 minutos.
Espectadores por Stream: Se calcula dividiendo la media de espectadores entre la media de streams, proporcionando una estimación del número de espectadores por cada transmisión.
Herramientas utilizadas
Power BI para la creación del dashboard.
Fuentes de datos: Datos de Twitch capturados durante la semana del 7 al 13 de noviembre de 2022.
Uso
Para explorar el dashboard, simplemente descarga el archivo .pbix y ábrelo en Power BI Desktop.

English
Power BI Dashboard: Video Game Streaming Analysis on Twitch
This project consists of an interactive dashboard developed in Power BI, analyzing live video game streams on the Twitch platform during the week of November 7th, 2022, to November 13th, 2022. The analysis provides detailed insights into streaming trends, with a special focus on the highly anticipated release of God of War Ragnarök, which launched on Wednesday, November 9th at 5am UTC+0.

Dataset Description
The analysis is based on two primary files:

StreamsInfo: Contains data on every game streamed on Twitch every 30 minutes, including the number of channels streaming the game and the number of viewers watching those channels. The time zone used is UTC+0 (London).
GamesInfo: Provides detailed information for each game such as ID, name, rating, genre, console, game mode, player perspective, and release date.
Objective
The goal of this dashboard is to provide a visual tool that allows users to explore trends in video game streaming and viewership on Twitch, with a particular focus on analyzing the popularity of various titles, including God of War Ragnarök during its launch week.

Key Features
Temporal analysis: Visualizes streaming activity and viewership over time in 30-minute intervals.
Key metrics: Average viewers and streams, along with the "Viewers per Stream" metric, which helps estimate the number of viewers per channel at a given moment.
Interactive filters: Allows filtering by game, genre, console, and more for specific analysis.
Impact of God of War Ragnarök’s release: Comparison of streaming activity before and after the game’s release.
Key Terminology in the Dashboard
Stream: A channel broadcasting content on Twitch.
Viewer: A person watching a specific stream.
Average Viewers and Streams: The concurrent average of data captures every 30 minutes.
Viewers per Stream: Calculated by dividing the average viewers by the average streams, providing an estimate of viewers per channel.
Tools Used
Power BI for dashboard creation.
Data sources: Twitch data captured during the week of November 7th to November 13th, 2022.
Usage
To explore the dashboard, simply download the .pbix file and open it in Power BI Desktop.

