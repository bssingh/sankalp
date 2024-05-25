Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-20.04-arm64"
  config.vm.provider "vmware_desktop" do |vmware|
   vmware.vmx["sata2.present"] = "TRUE"
   vmware.vmx["sata2.fileName"] = "boot_disk.vmdk"
  end
end

