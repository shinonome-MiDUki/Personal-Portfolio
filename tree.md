# ディレクトリ構造一覧

- [ディレクトリ構造一覧](#ディレクトリ構造一覧)
- [Oxoria](#oxoria)
- [ShellArc](#shellarc)
- [Shell DELTA](#shell-delta)

---

# Oxoria

```
.
├── API_reference.md
├── LICENSE
├── README.md
├── changelog.txt
├── icon_gen.py
├── pyproject.toml
├── src
│   └── oxoria
│       ├── __init__.py
│       ├── __main__.py
│       ├── _resources
│       │   ├── assets
│       │   │   ├── icon.png
│       │   │   └── initial_image.jpg
│       │   ├── docs
│       │   │   └── api_reference.html
│       │   └── init_config
│       │       ├── app_config.json
│       │       ├── editor_config.json
│       │       └── editor_config_ideal.json
│       ├── cmd
│       │   ├── __init__.py
│       │   ├── app_api.py
│       │   ├── canvas_api.py
│       │   ├── config_api.py
│       │   ├── cv_api.py
│       │   ├── io_api.py
│       │   ├── package_api.py
│       │   ├── resources_api.py
│       │   ├── search_api.py
│       │   ├── std_cv_cmd.py
│       │   └── std_menu_cmd.py
│       ├── global_var.py
│       ├── graphics
│       │   ├── __init__.py
│       │   └── img
│       │       └── image_hash.py
│       ├── io
│       │   ├── __init__.py
│       │   └── make_repo.py
│       ├── search
│       │   ├── __init__.py
│       │   ├── db_operate.py
│       │   ├── quantumize.py
│       │   └── use_vector.py
│       └── ui
│           ├── __init__.py
│           ├── canvas_area
│           │   ├── canvas.py
│           │   ├── ctx_menu.py
│           │   ├── graphics_entity.py
│           │   ├── graphics_item.py
│           │   ├── memo_item.py
│           │   └── resize_handle.py
│           ├── initial
│           │   └── initialise_ui.py
│           ├── main_ui.py
│           ├── outline
│           │   └── menu_bar.py
│           ├── resources_lib
│           │   ├── registering_dialog.py
│           │   └── side_panel.py
│           ├── tasktray
│           │   ├── __init__.py
│           │   └── tasktray_ui.py
│           ├── ui_var.py
│           └── ux_widgets
│               ├── console_line.py
│               ├── console_output.py
│               ├── settings_dialog.py
│               └── splitter.py
└── std_packages
    └── collage
        ├── __oxoplugin__.py
        ├── collage_ui.py
        └── grabcut_cv.py
```

---

# ShellArc

```
.
├── Dockerfile.dc
├── Dockerfile.itemi
├── Dockerfile.nullai
├── LICENSE
├── README.md
├── changelog.txt
├── discord_bot
│   ├── discord_connection.py
│   ├── discord_notice_webhook.py
│   └── emulator.py
├── docker-compose.yml
├── docker-compose.yml.template
├── null_ai_chat
│   ├── city_id.json
│   └── discord_chatbot.py
├── null_itemi_action
│   └── itemi_action.py
├── null_logo.png
├── project_ctx
│   ├── discord_config.json
│   ├── linker_setting.yaml
│   ├── project_setting.yaml
│   ├── project_settings.json
│   ├── requirements.txt
│   └── spreadsheet_map.json
├── project_ctx_main
│   ├── discord_config.json
│   ├── linker_setting.yaml
│   ├── project_setting.yaml
│   ├── project_settings.json
│   └── spreadsheet_map.json
├── project_ctx_template
├── pyproject.toml
├── requirements.txt
├── ruff_log_report.txt
├── shellarc_core_api_guide.md
├── shellarc_devkit
│   ├── cloud_access_check.py
│   ├── key_encoder.py
│   ├── local_dl
│   │   ├── backup_on_local.py
│   │   ├── init_settings.sh
│   │   └── requirements.txt
│   └── project_init_cli.py
├── shellarc_native
│   └── src
│       └── assets
├── src
│   └── shellarc_core
│       ├── __init__.py
│       ├── auth
│       │   ├── __init__.py
│       │   ├── access_database.py
│       │   ├── access_notion.py
│       │   ├── access_r2.py
│       │   └── access_spread_sheet.py
│       ├── cfg
│       │   ├── __init__.py
│       │   ├── cfg_io.py
│       │   └── spreadsheet_map_io.py
│       ├── cloudio
│       │   ├── __init__.py
│       │   ├── io_git.py
│       │   ├── io_notion.py
│       │   ├── io_r2.py
│       │   └── io_spreadsheet.py
│       ├── exception
│       │   ├── __init__.py
│       │   ├── exceptions.py
│       │   ├── structure_error.py
│       │   └── user_exception.py
│       ├── interface
│       │   ├── __init__.py
│       │   ├── interface_git.py
│       │   ├── interface_notion.py
│       │   ├── interface_r2.py
│       │   └── interface_spreadsheet.py
│       ├── process
│       │   ├── __init__.py
│       │   ├── query.py
│       │   ├── register.py
│       │   ├── requesting.py
│       │   ├── reviewing.py
│       │   ├── storyboard.py
│       │   ├── uploader.py
│       │   └── uploader_from_url.html.template
│       ├── sapyc
│       │   ├── __init__.py
│       │   └── sapyc_interpreter.py
│       ├── scheduler
│       │   ├── main_timer.py
│       │   └── manager.py
│       └── utils
│           ├── __init__.py
│           ├── file_operation.py
│           └── linker_parser.py
└── tests
    └── test_shellarc_core
        ├── emulator
        │   ├── emu_app.py
        │   ├── emu_backend.py
        │   ├── emulator_gb.py
        │   ├── mock_cmd.py
        │   └── run_emulator.py
        ├── mockio
        │   ├── mock_git_io.py
        │   ├── mock_notion_io.py
        │   ├── mock_r2_io.py
        │   └── mock_spreadsheet_io.py
        └── utils
            ├── emu_state.py
            └── mock_media.py
```

---

# Shell DELTA

```
.
├── LICENSE
├── README.md
├── manual.md
├── nudec
│   ├── CMakeLists.txt
│   ├── cmake_config.sh
│   ├── entry.cpp
│   ├── nudec_decode.cpp
│   ├── nudec_decode.h
│   ├── nudec_pack.cpp
│   ├── nudec_pack.h
│   └── pyproject.toml
├── pyproject.toml
├── sample_proj.sdproj
└── src
    └── shell_delta
        ├── __main__.py
        ├── _resources
        │   ├── expression_presets.json
        │   ├── fallback.png
        │   └── icon.jpg
        ├── expression
        │   ├── cel_engine.py
        │   └── tcl_engine.py
        ├── gb_var.py
        ├── graphics
        │   └── player.py
        ├── io
        │   └── io_sdproj.py
        ├── render
        │   ├── render.py
        │   ├── render_formats.py
        │   └── time_map.py
        ├── style
        │   ├── dark_default.py
        │   ├── elegant_light.py
        │   ├── kawaii_pink.py
        │   └── pure_skyblue.py
        ├── ui
        │   ├── expression_editor.py
        │   ├── expression_widgets.py
        │   ├── main_win
        │   │   ├── main_win.py
        │   │   ├── main_win_events.py
        │   │   ├── main_win_io.py
        │   │   ├── main_win_playback.py
        │   │   └── main_win_ui.py
        │   ├── opengl.py
        │   └── render_dialog.py
        └── utils
            └── editing_utils.py
```
