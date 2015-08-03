# Folder-creation
directory node[:sumologic][:tmp_path] do
    owner 'root'
    group 'root'
    mode 0755
    action 'create'
  end
