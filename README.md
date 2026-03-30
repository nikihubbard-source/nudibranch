
# nudibranch

Colour palettes inspired by intertidal and shallow rocky reef nudibranchs and sea slugs 
photographed in NSW, Australia.

## Installation
install.packages("devtools")
devtools::install_github("nikihubbard-source/nudibranch")

## Usage
library(nudibranch)

# See all palettes
nudibranch_palette()

# Get a palette
nudibranch_palette("hypselodoris")

# Use with ggplot2
ggplot(data, aes(x, y, colour = group)) +
  scale_colour_nudibranch("hypselodoris")

## Palettes

### Hydatina
![hydatina](man/figures/01 Hydatina.png)

### Hypselodoris
![hypselodoris](man/figures/02 Hypselodoris.png)

### Doriprismatica
![bullina](man/figures/03 Doriprismatica.png)

### Bullina
![elysia](man/figures/04 Bullina.png)

### Elysia
![dolabrifera](man/figures/05 Elysia.png)

### Dolabrifera
![carminodoris](man/figures/06 Dolabrifera.png)

### Dendrodoris
![dendrodoris](man/figures/07 Dendrodoris.png)

### Aplysia
![aplysia](man/figures/08 Aplysia.png)

### Haloa
![haloa](man/figures/09 Haloa.png)

### Carminodoris
![ceratosoma](man/figures/010 Carminodoris.png)

### Jorunna
![jorunna](man/figures/011 Jorunna.png)

### Ceratosama
![doriprismatica](man/figures/012 Ceratosama.png)
