icon_sizes = ['16','24','32', '48', '64', '128']

foreach i : icon_sizes
    install_data(
        join_paths('icons/', meson.project_name() + '.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons', 'hicolor', i + 'x' + i, 'apps')
    )
endforeach

foreach i : icon_sizes
    install_data(
        join_paths('icons/', meson.project_name() + '.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons/hicolor', i + 'x' + i, 'mimetypes')
    )
endforeach

install_data(
    'icons/' + meson.project_name() + '.svg',
    install_dir: join_paths(get_option('datadir'), 'icons/hicolor/scalable/apps')
)

install_data(
    meson.project_name() + '.contract',
    install_dir: join_paths(get_option('datadir'), 'contractor')
)

install_data(
    meson.project_name() + '.desktop',
    install_dir: join_paths(get_option('datadir'), 'applications')
)

install_data(
    meson.project_name() + '.appdata.xml',
    install_dir: join_paths(get_option('datadir'), 'metainfo')
)
