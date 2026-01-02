# Dotfiles

Mis archivos de configuración gestionados con GNU Stow.

## Requisitos

- GNU Stow
- Fuente: RobotoMono Nerd Font

## Instalación
```bash
# Clonar repositorio
git clone https://github.com/KyriuxDev/dotfiles.git
cd ~/dotfiles

# Aplicar configuraciones
stow conky
```

## Aplicaciones configuradas

### Conky
Monitor de sistema con tema oscuro personalizado.
- Resolución optimizada: 1366x768
- Muestra: CPU, RAM, red (wlan0), batería, procesos
- Tema: Oscuro con transparencia

Para iniciar: `conky`

## Uso de Stow
```bash
# Instalar dotfiles
stow <nombre-app>

# Desinstalar
stow -D <nombre-app>

# Reinstalar (después de cambios)
stow -R <nombre-app>
```

