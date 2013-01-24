OVPN_MGMT_URL := 'http://search.cpan.org/CPAN/authors/id/M/ME/MEYEAARD/Net-OpenVPN-Manage-0.02.tar.gz'
OVPN_MGMT_FILE := 'Net-OpenVPN-Manage.tar-gz'

all: openvpn-manage

openvpn-manage:
	@wget -N -q $(OVPN_MGMT_URL) -O $(OVPN_MGMT_FILE)
	@tar --wildcards --strip-components=2 -xzf $(OVPN_MGMT_FILE) 'Net-OpenVPN-Manage*/lib/*pm'
	@echo Net::OpenVPN::Manage updated


