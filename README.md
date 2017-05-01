# gitdns

Easy DNS via git


## Install

	make DESTDIR=/ PREFIX=/usr install


## Globals

	CONFIGDIR="$HOME/.config/gitdns"
	CONFIG="$CONFIGDIR/config"
	DNS="$CONFIGDIR/dns"


## Configuration

Configure the git remote in `$CONFIG`

	{ "remote" : "..." }


## Usage

	gitdns <command> <...args>

### info

	gitdns info

### put

	gitdns put <hostname> <ip>

### get

	gitdns get <hostname>

### pull

	gitdns pull

### push

	gitdns push

### sync

	gitdns sync

### listen

	gitdns listen

### broadcast

	gitdns broadcast
