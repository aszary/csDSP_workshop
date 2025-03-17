# Pulsary

Pobieramy projekt:

`git clone https://github.com/aszary/csDSP_workshop.git`

## Uruchamiamy Wirtualną Maszynę Pulsarową

```
ssh_tunnel.sh port_number     # uruchamiamy na lokalnym komputerze (np.5901)
ssh.sh                        # łączymy się z serwerem kopernik
cd warsztaty/
./run.sh name display_port            # uruchamiamy Wirtualną Maszynę Pulsarową
./startx.sh port_number display_port  # serwer do wyświetlania
...
...
...
xtigervncviewer localhost:port_number        # łączymy się z serwerem do wyświetlania
```
